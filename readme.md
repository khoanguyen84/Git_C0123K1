# Learning Git Collaborators

## Lệnh thường gặp

1. Tạo nhánh mới - Cách 1
+ Bước 1: ```git branch <branch_name> ``` ví dụ: ```git branch development ```
+ Bước 2: ```git checkout <branch_name> ``` ví dụ: ```git checkout development ```

2. Tạo nhánh mới - Cách 2
+ 1 bước:  ```git checkout -b <branch_name>``` ví dụ: ``` git checkout -b khoa_dev ```

2. Lấy mã nguồn mới về
+ Bước 1: kiểm tra ```git fetch ```
+ Bước 2: lấy mã nguồn ```git pull -u origin <branch_name> ``` ví dụ: ```git pull -u origin development ```