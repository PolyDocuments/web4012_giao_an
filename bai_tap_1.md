# Đề luyện tập

- CRUD 3 bảng:
    - users
        - id
        - name
        - date_of_birth
        - email <unique>
        - password
        - role
            - 1: user <default>
            - 2: admin
        - avatar
    - posts:
        - id
        - title
        - content
        - likes: integer
    - post_images:
        - id
        - post_id
        - url
- Yêu cầu:
    - User:
        - Được đăng kí, đăng nhập, xem các bài Post.
        - Chỉnh sửa thông tin cá nhân. 
    - Admin: được CRUD User, Post, PostImage.
    - 1 bài Post có thể có nhiều PostImage.
    - Cần check validate/middleware đầy đủ.
