# AreaPickerView_swift
areapicker in china, easy to use. 中国的地区选择器.简单易用.

![Alt Text](https://github.com/chquanquan/AreaPickerView_swift/blob/master/Simulator%20Screen%20Shot%202017年1月28日%2020.10.22.png)


只需要实现三个代理方法

internal func cancel(areaToolbar: AreaToolbar, textField: UITextField, locate: Location, item: UIBarButtonItem) {
//还原原来的值......
}

internal func sure(areaToolbar: AreaToolbar, textField: UITextField, locate: Location, item: UIBarButtonItem) {
//设置新值
}

internal func statusChanged(areaPickerView: AreaPickerView, pickerView: UIPickerView, textField: UITextField, locate: Location) {
//立即显示新值
}


