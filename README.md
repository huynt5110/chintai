# MICE

## Overview

JAPAN MEETING & INCENTIVE

## Cấu trúc thư mục: 
* .tmp : chứa js và css tạm thời (không edit)
* dist : chứa nội dung đã buid ra (sản phẩm cuối để giao)
* src : chưa nội dung trang đang thao tác (chỉ css trong folder scss)

## List gulp task 
* imgaes: nén hình, copy hình sang folder dist
* copy : copy source sang folder dist
* style : convert từ scss sang css (copy vào .tmp và dist)
* babelfy: Convert từ ES6 sang ES5 
* browserify (nén các file javascript thành 1: main.min.js)
* html: kiểm tra html 
* clean: xóa bộ nhớ tạm, làm rỗng folder dist 
* serve: chạy server local, reload lại trang mỗi khi có js / css thay đổi
* serve:css : chạy server, update lại style khi có thay đổi css
* serve:dist : chạy server với phiên bản cuối cùng (folder dist) 
* default : Chạy các task trên để build ra sản phẩm cuối (folder dist)

## License

Apache 2.0  
Copyright 2017 Brain
