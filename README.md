### Ti.MaterilaDesignTextField###

This module is classic version of [Nádson Fernando's awesome alloay module input-materialdesign](http://gitt.io/component/input-materialdesign)

![](https://github.com/NadsonFernando/input-materialdesign-widget/raw/master/asset/example-input.gif) ![](https://github.com/NadsonFernando/input-materialdesign-widget/raw/master/asset/androidl.png)


Usage
=====

1. you have to embed the module by

~~~
gittio install de.appwerft.materialtextfield
~~~


2.

~~~
var MaterialTextfield = require('vendor/materialtextfield');

module.exports = function() {
    var self = Ti.Ui.createWindow();
    var container = Ti.UI.createScrollView({layout : 'vertical',scrollType:'vertical'});
    self.add(container);
    container.add(MaterialTextfield.createView({
        titleHint : 'Erstes Eingabefeld',
        top : 50
    }));
    container.add(MaterialTextfield.createView({
        titleHint : 'Zweites Eingabefeld',
        top : 50
    }));
    container.add(MaterialTextfield.createView({
        titleHint : 'Drittes Eingabefeld',
        top : 50
    }));
    return self;
};

~~~

Properties
==========

Please look to [http://gitt.io/component/input-materialdesign](http://gitt.io/component/input-materialdesign)