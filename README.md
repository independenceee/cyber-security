I. Lý thuyết

1. Khái niệm kiểm thử phần mềm, kiểm định, Thẩm định. Đặc điểm của kiểm thử phần mềm ?
- Kiểm thử phần mềm: là quá trình đánh giá một hệ thống hoặc thành phần phần mềm để tìm lỗi, đảm bảo chất lượng và xác minh rằng sản phẩm hoạt động đúng như mong đợi. Quá trình này bao gồm thực hiện phần mềm với mục đích xác định lỗi hoặc các vấn đề cần khắc phục.
- Kiếm định: là quá trình đánh giá xem liệu sản phẩm phần mềm có tuân thủ các đặc tả yêu cầu kỹ thuật, tài liệu thiết kế hay không. Mục tiêu là đảm bảo rằng sản phẩm "làm đúng việc nó phải làm". Đây thường là một hoạt động tĩnh như kiểm tra mã nguồn, tài liệu hoặc review.
- Thẩm định: Là quá trình kiểm tra xem liệu sản phẩm phần mềm có đáp ứng yêu cầu thực tế của người dùng hay không. Mục tiêu là đảm bảo rằng sản phẩm "làm điều đúng đắn". Đây là một hoạt động động, thường liên quan đến việc chạy phần mềm.
- Đặc điểm của kiểm thử phần mềm: 
+ Không bao giờ chứng minh được phần mềm không có lỗi: Kiểm thử chỉ có thể chỉ ra sự hiện diện của lỗi, không phải sự vắng mặt của lỗi.
+ Kiểm thử là một quá trình sáng tạo: Cần phải hiểu rõ cách hệ thống hoạt động và dự đoán các tình huống có thể phát sinh lỗi.
+ Kiểm thử phụ thuộc vào bối cảnh: Các phương pháp kiểm thử và tiêu chí chất lượng sẽ khác nhau tùy thuộc vào loại phần mềm (web, mobile, enterprise, etc.).
+ Kiểm thử không chỉ là tìm lỗi: Nó còn giúp cải thiện chất lượng sản phẩm, tăng tính ổn định và độ tin cậy.
+ Có thể thực hiện ở mọi giai đoạn phát triển phần mềm: Từ khi thiết kế yêu cầu đến khi triển khai, kiểm thử đều có thể diễn ra.
+ Cần được lập kế hoạch cẩn thận: Quy trình kiểm thử cần được định nghĩa rõ ràng, với các trường hợp thử nghiệm, kịch bản kiểm thử và mục tiêu cụ thể.
+ Có giới hạn về thời gian và nguồn lực: Không thể kiểm thử toàn bộ các tình huống hoặc trạng thái của phần mềm; cần tập trung vào các khu vực có nguy cơ cao.
+ Kiểm thử nên độc lập: Để đảm bảo khách quan, đội ngũ kiểm thử nên độc lập với đội phát triển.

3. So sánh giữa kiểm định và thẩm định.

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


5. Quy trình kiểm thử phần mềm gồm những bước nào ?
6. So sánh kiểm thử hộp đen và kiểm thử hộp trắng ?
7. Nêu một số mức kiểm thử phần mềm ?
8. Hãy nêu một ví dụ về lỗi phần mềm và ảnh hưởng của nó đối với người dùng cũng như nhà sản xuất phần mềm ?
9. Nêu sự khác biệt giữa hai quá trình: kiểm định và thẩm định trong quy trình kiểm thử phần mềm ?
10. Quan niệm sau đây là đúng hay sai và hãy đưa ra lý do của mình: “Kiểm thử phần mềm là qui trình chứng minh phần mềm không có lỗi” ?
11. Hãy phân biệt các khái niệm “Error”, “Fault” và “Failure” trong kiểm thử phần mềm ?
12. Hãy trình bày khái niệm về mục đích của một kiểm thử viên trong kiểm thử phần mềm ?
13. Tại sao phải kiểm thử phần mềm? Hãy trình bày hiểu biết của bạn về các quan niệm không đúng trong kiểm thử phần mềm ?
14. Hãy trình bày sự hiểu biết của bạn về kỹ thuật kiểm thử luồng dữ liệu trong kiểm thử hộp trắng ?

II. Bài tập về kiểm thử hộp trắng 
III. Bài tập về kiểm thử hộp đen
