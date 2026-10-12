# Tasks API Project

Bài tập nhóm xây dựng hệ thống RESTful API quản lý công việc sử dụng Flask và chuẩn OpenAPI 3.0.

## Minh chứng kiểm thử Endpoints qua 5 ảnh chụp Swagger UI

- **Ảnh 1 (`POST /tasks`)**: Tạo thành công công việc mới với tiêu đề `"Hi tớ chào cậu"`, nhận phản hồi mã `201` kèm thông tin task vừa tạo[cite: 9].  
  ![POST Task](images/Screenshot%202026-10-12%20234341.png)

- **Ảnh 2 (`GET /tasks`)**: Lấy danh sách toàn bộ công việc, hiển thị đầy đủ các task hiện có bao gồm cả task mới tạo (`id: 4`) với mã `200`[cite: 13].  
  ![GET Tasks](images/Screenshot%202026-10-12%20234405.png)

- **Ảnh 3 (`GET /tasks/{id}`)**: Truy vấn thành công thông tin chi tiết của công việc có ID là `4`[cite: 12].  
  ![GET Task by ID](images/Screenshot%202026-10-12%20234430.png)

- **Ảnh 4 (`PUT /tasks/{id}`)**: Cập nhật thành công tiêu đề thành `"Hi hi hi hi hi"` và trạng thái hoàn thành thành `true` cho task ID `4`[cite: 11].  
  ![PUT Task](images/Screenshot%202026-10-12%20234500.png)

- **Ảnh 5 (`DELETE /tasks/{id}`)**: Xóa thành công công việc theo ID (`id: 2`), hệ thống trả về thông báo `Deleted successfully`[cite: 10].  
  ![DELETE Task](images/Screenshot%202026-10-12%20234524.png)

