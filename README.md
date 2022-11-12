Coding coding.

1. origin: origin/main
2. feat- feature: feat/name: feat/addproduct 
3. fix: sửa code - báo hiệu cho người khác biết là nhánh này là sửa bug của code cũ fix/bugaddproduct
4. refactor: sửa code (không phải để sửa bug mà để thay đổi code) refactor/...

- tạo kho lưu trữ mới.

1. git init 

2. checkxem code  có README.md hay chưa nếu có rồi thì git add . chưa có thì git add README.md

3. git add . (Đồng ý tất cả các file mà coder thay đổi)

4. git commit -m "first commit".

5. git branch -M main

6. git remote add origin https://github.com/NqDyK2/testgithub.git

7. git push -u origin main 

- Code tiếp dự án và đẩy lên.

1. stage all changes

2. viết mess và commit 

3. sync changes

+ LÀM VIỆC GIT VỚI TEAM:

 - ĐẨY CODE MỚI SANG NHÁNH KHÁC

 1. compare & pull request

 2. base và compare

 Base: Nơi nhận code mới.

 Compare: là nơi chứa code mới mà mình vừa code xong 

 3. Sau khi tạo pull request xong đẩy sang trang tiếp theo thì không được merge luôn mà công việc merge là của leader
    a. Thành viên: tắt git 
    b. Lead: check commits check files change, check sản phẩm trên nhánh muốn merge.


- CODE CHỨC NĂNG MỚI:

CODE MỚI CODE MỚI CODE MỚI.
     - TẠO NHÁNH MỚI TỪ DEV VÀ CODE CHỨC NĂNG.

     NOTE: LUÔN PHẢI TẠO NHÁNH MỚI TỪ (ORIGIN/DEV).

    ABCXYZ
    123456
    QWERTY