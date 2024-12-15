I. Lý thuyết

1. Khái niệm kiểm thử phần mềm, kiểm định, Thẩm định. Đặc điểm của kiểm thử phần mềm ?
2. So sánh giữa kiểm định và thẩm định.

| **Tiêu chí**                  | **Kiểm định (Verification)**                                       | **Thẩm định (Validation)**                                     |
|-------------------------------|--------------------------------------------------------------------|----------------------------------------------------------------|
| **Định nghĩa**                | Quá trình kiểm tra xem sản phẩm phần mềm có đáp ứng các yêu cầu kỹ thuật và tài liệu thiết kế hay không. | Quá trình kiểm tra xem sản phẩm phần mềm có đáp ứng các yêu cầu thực tế của người dùng hay không. |
| **Mục tiêu**                  | Đảm bảo rằng sản phẩm **được xây dựng đúng cách** (Build the product right). | Đảm bảo rằng sản phẩm **đúng như yêu cầu** (Build the right product). |
| **Thời điểm thực hiện**        | Thực hiện trong giai đoạn phát triển (trước khi chạy phần mềm).  | Thực hiện sau khi phần mềm được phát triển (khi chạy phần mềm). |
| **Phương pháp**               | - Dựa trên các hoạt động tĩnh: xem xét tài liệu, đánh giá mã nguồn, thiết kế, kiểm tra mô hình, v.v. | - Dựa trên các hoạt động động: chạy phần mềm, thực hiện kiểm thử, tương tác với sản phẩm. |
| **Công cụ sử dụng**           | Dùng công cụ kiểm tra mã nguồn, tài liệu thiết kế, tài liệu yêu cầu (như walkthrough, review). | Dùng công cụ chạy phần mềm, thực hiện kiểm thử (như functional testing, usability testing). |
| **Loại kiểm tra**             | Kiểm tra các yêu cầu kỹ thuật (Technical Requirements).          | Kiểm tra các yêu cầu nghiệp vụ (Business Requirements).        |
| **Người thực hiện**           | Thường do nhóm phát triển thực hiện.                              | Thường do nhóm kiểm thử hoặc người dùng thực hiện.             |
| **Ví dụ**                     | - Xác minh xem tài liệu thiết kế có tuân thủ yêu cầu không.       | - Kiểm tra xem phần mềm có cung cấp chức năng đúng với mong đợi của người dùng hay không. |
| **Tính chất**                 | Mang tính chất phòng ngừa lỗi.                                    | Mang tính chất phát hiện lỗi.                                  |
| **Kết quả**                   | Kết quả là tài liệu hoặc mô hình đạt yêu cầu.                     | Kết quả là một sản phẩm phần mềm phù hợp với thực tế sử dụng.   |

## **Kết luận**
- **Kiểm định** tập trung vào việc đảm bảo quy trình phát triển được thực hiện đúng (đúng theo yêu cầu kỹ thuật và tài liệu).
- **Thẩm định** tập trung vào việc xác minh rằng sản phẩm cuối cùng đúng với mong muốn và nhu cầu của người dùng.

Hai quá trình này bổ trợ lẫn nhau để đảm bảo chất lượng phần mềm toàn diện.

3. Quy trình kiểm thử phần mềm gồm những bước nào ?

# Quy Trình Kiểm Thử Phần Mềm
Quy trình kiểm thử phần mềm (Software Testing Process) bao gồm các bước cơ bản sau đây, áp dụng linh hoạt tùy thuộc vào từng dự án và mô hình phát triển phần mềm (VD: Agile, Waterfall):
## **1. Lập Kế Hoạch Kiểm Thử (Test Planning)**
- Xác định phạm vi kiểm thử, mục tiêu, tài nguyên và thời gian cần thiết.
- Chọn công cụ kiểm thử, kỹ thuật kiểm thử.
- Lập kế hoạch về môi trường kiểm thử và các rủi ro.
- Tạo tài liệu **Test Plan** để định hướng hoạt động kiểm thử.
## **2. Phân Tích và Thiết Kế Kiểm Thử (Test Analysis & Design)**
- **Phân tích yêu cầu**: Hiểu rõ các yêu cầu phần mềm từ tài liệu mô tả yêu cầu (SRS, User Stories).
- **Thiết kế trường hợp kiểm thử (Test Cases)**: Xác định các kịch bản kiểm thử dựa trên yêu cầu chức năng và phi chức năng.
- Xây dựng dữ liệu kiểm thử (Test Data).
- Thiết lập môi trường kiểm thử (Test Environment Setup).
## **3. Thiết Lập Môi Trường Kiểm Thử (Test Environment Setup)**
- Cấu hình phần mềm và phần cứng để tạo môi trường kiểm thử phù hợp.
- Tích hợp công cụ hỗ trợ kiểm thử (nếu cần).
- Đảm bảo môi trường kiểm thử sẵn sàng trước khi thực thi kiểm thử.
## **4. Thực Thi Kiểm Thử (Test Execution)**
- Thực hiện các trường hợp kiểm thử (Test Cases) đã thiết kế.
- Ghi nhận kết quả kiểm thử (Passed/Failed).
- Báo cáo các lỗi (Defects) tìm thấy cho đội phát triển.
## **5. Quản Lý Lỗi (Defect Reporting & Management)**
- Theo dõi và báo cáo lỗi phát hiện trong kiểm thử.
- Làm việc với đội phát triển để khắc phục lỗi.
- Kiểm tra lại các lỗi đã sửa (Re-testing) và đảm bảo chúng không ảnh hưởng đến chức năng khác (Regression Testing).
## **6. Đánh Giá và Kết Thúc Kiểm Thử (Test Closure)**
- Đánh giá chất lượng phần mềm và hiệu quả của quy trình kiểm thử.
- Chuẩn bị tài liệu báo cáo kiểm thử (Test Summary Report).
- Phân tích bài học kinh nghiệm để cải tiến quy trình kiểm thử cho tương lai.
## **Lưu Ý Quan Trọng**
- Kiểm thử phần mềm thường diễn ra đồng thời với các giai đoạn phát triển trong mô hình Agile.
- Luôn kết hợp kiểm thử tự động (Automation Testing) và kiểm thử thủ công (Manual Testing) khi cần thiết.
- Quy trình kiểm thử nên được tùy chỉnh phù hợp với yêu cầu dự án.

4. So sánh kiểm thử hộp đen và kiểm thử hộp trắng ?

# So sánh kiểm thử hộp đen và kiểm thử hộp trắng

Kiểm thử hộp đen và kiểm thử hộp trắng là hai phương pháp kiểm thử phần mềm có cách tiếp cận và mục tiêu khác nhau. Dưới đây là bảng so sánh giữa hai loại kiểm thử này:

| **Tiêu chí**          | **Kiểm thử hộp đen**                                  | **Kiểm thử hộp trắng**                                |
|------------------------|-------------------------------------------------------|------------------------------------------------------|
| **Khái niệm**         | Kiểm thử chức năng của hệ thống mà không cần biết về cấu trúc bên trong hoặc mã nguồn. | Kiểm thử tập trung vào cấu trúc bên trong, logic và mã nguồn của phần mềm. |
| **Tên gọi khác**      | Kiểm thử hộp kín, kiểm thử dựa trên đầu vào và đầu ra. | Kiểm thử hộp mở, kiểm thử cấu trúc, kiểm thử mã nguồn. |
| **Phạm vi**           | Đánh giá xem phần mềm có hoạt động đúng theo yêu cầu không. | Đánh giá tính chính xác của logic bên trong và cấu trúc mã. |
| **Mục tiêu**          | Xác minh rằng phần mềm thực hiện đúng chức năng được chỉ định. | Đảm bảo rằng tất cả các đường dẫn mã được thực hiện và hoạt động như mong đợi. |
| **Kiến thức yêu cầu** | Không yêu cầu hiểu biết về mã nguồn hoặc cấu trúc bên trong. | Yêu cầu kiến thức sâu về mã nguồn, cấu trúc bên trong, và thuật toán. |
| **Người thực hiện**   | Tester hoặc người dùng cuối, không cần là lập trình viên. | Lập trình viên hoặc tester có kỹ năng lập trình. |
| **Phương pháp**       | Dựa trên các trường hợp kiểm thử được tạo từ tài liệu yêu cầu và đặc tả kỹ thuật. | Dựa trên việc phân tích mã nguồn và kiểm tra từng phần của cấu trúc mã. |
| **Ưu điểm**           | - Đơn giản, không cần hiểu mã nguồn. <br> - Phát hiện lỗi trong chức năng hoặc giao diện người dùng. | - Đảm bảo kiểm tra toàn diện mã nguồn. <br> - Phát hiện các lỗi liên quan đến logic, luồng dữ liệu. |
| **Nhược điểm**        | - Không phát hiện được lỗi logic hoặc cấu trúc mã. <br> - Có thể bỏ sót lỗi nếu các trường hợp kiểm thử không đủ. | - Mất thời gian do phải phân tích mã nguồn. <br> - Không phát hiện được lỗi về yêu cầu nếu mã đúng logic. |
| **Ví dụ**             | - Kiểm thử giao diện người dùng. <br> - Kiểm tra đầu vào và đầu ra của một chức năng. | - Kiểm tra độ phủ của mã nguồn (code coverage). <br> - Kiểm tra các điều kiện và nhánh logic. |

## **Khi nào sử dụng?**
- **Kiểm thử hộp đen**: Khi cần kiểm tra chức năng và tính năng của phần mềm từ góc độ người dùng hoặc khách hàng.
- **Kiểm thử hộp trắng**: Khi muốn đảm bảo chất lượng mã nguồn và logic bên trong phần mềm.

Sự kết hợp cả hai phương pháp thường được sử dụng để đạt được phạm vi kiểm thử toàn diện.

5. Nêu một số mức kiểm thử phần mềm ?

# Các Mức Kiểm Thử Phần Mềm

Kiểm thử phần mềm thường được chia thành nhiều **mức kiểm thử** nhằm đảm bảo chất lượng sản phẩm từ cấp độ nhỏ nhất đến toàn bộ hệ thống. Dưới đây là các mức kiểm thử phổ biến:

## 1. Kiểm thử đơn vị (Unit Testing)
- **Mục đích:** Kiểm tra từng đơn vị nhỏ nhất của phần mềm, chẳng hạn như hàm, module hoặc class.  
- **Người thực hiện:** Thường do lập trình viên đảm nhận.  
- **Công cụ hỗ trợ:** NUnit, JUnit, xUnit, v.v.  

## 2. Kiểm thử tích hợp (Integration Testing)
- **Mục đích:** Kiểm tra sự tương tác giữa các module hoặc thành phần đã được tích hợp.  
- **Người thực hiện:** Thường do tester hoặc lập trình viên thực hiện.  
- **Kỹ thuật:**  
  - Top-down (tích hợp từ trên xuống).  
  - Bottom-up (tích hợp từ dưới lên).  
  - Sandwich (kết hợp cả hai).  
- **Công cụ hỗ trợ:** Postman, SoapUI, v.v.  

## 3. Kiểm thử hệ thống (System Testing)
- **Mục đích:** Kiểm tra toàn bộ hệ thống phần mềm sau khi tích hợp, đảm bảo đáp ứng các yêu cầu đã đặt ra.  
- **Người thực hiện:** Thường do đội kiểm thử chuyên nghiệp (QA).  
- **Loại kiểm thử:** Kiểm thử chức năng, kiểm thử phi chức năng (hiệu năng, bảo mật, khả năng chịu tải, v.v.).  

## 4. Kiểm thử chấp nhận (Acceptance Testing)
- **Mục đích:** Đánh giá liệu phần mềm có đáp ứng yêu cầu và kỳ vọng của khách hàng hay không.  
- **Người thực hiện:** Người dùng cuối, khách hàng hoặc đội QA đại diện cho người dùng.  
- **Loại kiểm thử:**  
  - **Alpha Testing:** Do đội nội bộ thực hiện trước khi phát hành.  
  - **Beta Testing:** Do người dùng cuối thực hiện trong môi trường thực tế.  

---

### Các Kiểm Thử Bổ Sung
Ngoài các mức kiểm thử chính, còn có thể bao gồm:
- **Kiểm thử hồi quy (Regression Testing):** Kiểm tra phần mềm sau khi có thay đổi hoặc cập nhật.  
- **Kiểm thử khói (Smoke Testing):** Kiểm tra nhanh các chức năng cơ bản nhất để đảm bảo hệ thống không bị lỗi nghiêm trọng.  
- **Kiểm thử khả năng tương thích (Compatibility Testing):** Đảm bảo phần mềm hoạt động tốt trên nhiều môi trường, thiết bị khác nhau.  

Mỗi mức kiểm thử đóng vai trò quan trọng trong việc đảm bảo chất lượng toàn diện của sản phẩm phần mềm.



8. Hãy nêu một ví dụ về lỗi phần mềm và ảnh hưởng của nó đối với người dùng cũng như nhà sản xuất phần mềm ?
9. Nêu sự khác biệt giữa hai quá trình: kiểm định và thẩm định trong quy trình kiểm thử phần mềm ?
10. Quan niệm sau đây là đúng hay sai và hãy đưa ra lý do của mình: “Kiểm thử phần mềm là qui trình chứng minh phần mềm không có lỗi” ?
11. Hãy phân biệt các khái niệm “Error”, “Fault” và “Failure” trong kiểm thử phần mềm ?

- Error (Lỗi):
+ Định nghĩa: Là sự bất chính xác trong đoạn mã , tài liệu, các giai đoạn phát triển của phần mềm.
+ Nguyên nhân: Thường do các lỗi của lập trình viên, thiếu sót trong thiết kế, hoặc các yêu cầu không chính xác.
+ Ví dụ:
* Một giá trị biến bị sai.
* Một số lỗi toán học như chia cho số 0.
* Sai sót trong thuật toán sử lý dữ liệu.


13. Hãy trình bày khái niệm về mục đích của một kiểm thử viên trong kiểm thử phần mềm ?
14. Tại sao phải kiểm thử phần mềm? Hãy trình bày hiểu biết của bạn về các quan niệm không đúng trong kiểm thử phần mềm ?
15. Hãy trình bày sự hiểu biết của bạn về kỹ thuật kiểm thử luồng dữ liệu trong kiểm thử hộp trắng ?

II. Bài tập về kiểm thử hộp trắng 
III. Bài tập về kiểm thử hộp đen
