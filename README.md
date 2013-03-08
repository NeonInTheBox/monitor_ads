monitor_ads
===========

shows ads on monitor


basic function: slide show

1. if usb drive is inserted, play files in usb drive (root directory), store images to local and upload to server when wifi is on
1. else if internet is on, play internet images
1. else play cached


when mouse is clicked, play menu, else play slideshow

menu: setup wifi, select album


image, title

weekdays special

holidays special

two channels: 1: big, 2: small (the bottom ones)

server logic: given a day, retrieve the set of big items and small items

if its close to holiday, choose holiday, otherwise choose weekday

data structure

1. table: weekday/holiday, 1-7/holidayname, image_url, image_title

2. folder: weekdays and holidays

weekdays/1~7/big/<imagename>.jpg, weekdays/1~7/small/<imagename>.jpg

holidays/<holidayname>/bigorsmall




### ads server

Administrator dashboard: http://nitbtest.orbitopenadserver.com/admin
Advertiser dashboard: http://nitbtest.orbitopenadserver.com/advertiser

