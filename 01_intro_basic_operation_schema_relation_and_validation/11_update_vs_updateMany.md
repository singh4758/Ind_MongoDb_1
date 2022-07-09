![](./screenshots/11_update_vs_updateMany/2022-06-26-13-20-24.png)

![](./screenshots/11_update_vs_updateMany/2022-06-26-13-21-49.png)

![](./screenshots/11_update_vs_updateMany/2022-06-26-13-23-06.png)
In updateOne we can not send data as document to update the field.
It will throw the error.

![](./screenshots/11_update_vs_updateMany/2022-06-26-13-37-30.png)
Difference between update and updateOne is update replace the old data with new data
whereas updateOne or updateMany only affects the field which will be written in 
updating data.

![](./screenshots/11_update_vs_updateMany/2022-06-26-13-39-07.png)
replaceOne is same as update but with only one document at a time.