# Chương 1

1. Phát biểu nào mô tả đúng nhất về khái niệm ethical hacker? => Người mô phỏng một kẻ tấn công để đánh giá tình trạng bảo mật của mạng.
2. Thuật ngữ nào mô tả nhóm tội phạm mạng có tài trợ tốt và động cơ mạnh mẽ, sử dụng các kỹ thuật tấn công mới nhất để đạt được lợi nhuận tài chính? => Tội phạm có tổ chức
3. Loại tác nhân đe dọa nào sử dụng tội phạm mạng để đánh cắp dữ liệu nhạy cảm và công khai nhằm làm xấu mặt mục tiêu? => Hacktivist
4. Tấn công được nhà nước bảo trợ là gì? => Tấn công do chính phủ thực hiện để làm gián đoạn hoặc đánh cắp thông tin từ quốc gia khác.
5. Tấn công nội bộ là gì? => Tấn công bởi nhân viên bất mãn trong tổ chức.
6. Kiểm tra thâm nhập ứng dụng nhằm đánh giá loại lỗ hổng bảo mật nào? => Lỗi logic (logic flaws)
7. Hai tài nguyên nào được kiểm tra trong kiểm tra thâm nhập cơ sở hạ tầng mạng? => Máy chủ AAA (AAA servers), Hệ thống ngăn chặn xâm nhập (IPSs)
8. Khi kiểm tra ứng dụng web, cần kiểm tra truy cập vào tài nguyên nào? => Cơ sở dữ liệu phụ trợ (Back-end databases)
9. Mục đích của chương trình bug bounty là gì? => Thưởng cho các chuyên gia an ninh khi phát hiện lỗ hổng bảo mật.
10. Bài kiểm tra thâm nhập môi trường bán biết được đặc trưng bởi điều gì? => Là một cách tiếp cận lai giữa kiểm tra không biết và biết trước.
11. Bài kiểm tra thâm nhập môi trường đã biết (Known Environment Test) có đặc điểm gì? => Người kiểm tra được cung cấp sơ đồ mạng, địa chỉ IP, cấu hình và thông tin đăng nhập người dùng.
12. Loại kiểm tra thâm nhập nào chỉ cung cấp thông tin hạn chế, như tên miền và địa chỉ IP nằm trong phạm vi? => Kiểm tra môi trường chưa biết (Unknown Environment Test).
13. Khớp các phương pháp kiểm tra thâm nhập với mô tả tương ứng:
MITRE ATT&CK: Bộ tập hợp các ma trận chiến thuật và kỹ thuật mà kẻ tấn công sử dụng khi chuẩn bị tấn công.
OWASP WSTG: Hướng dẫn chi tiết về kiểm tra bảo mật ứng dụng web.
NIST SP 800-115: Cung cấp hướng dẫn lập kế hoạch và thực hiện kiểm tra bảo mật thông tin.
OSSTMM: Đưa ra các phương pháp kiểm tra bảo mật nhất quán và có thể lặp lại.
PTES: Cung cấp thông tin về các kiểu tấn công và phương pháp thực hiện.
14. Ba giai đoạn trong Chuẩn thực thi kiểm tra thâm nhập (PTES) là gì? (Chọn ba)
Mô hình hóa mối đe dọa (Threat Modeling)
Khai thác (Exploitation)
Báo cáo (Reporting)
15. Hai giai đoạn nào thuộc Khung đánh giá bảo mật hệ thống thông tin (ISSAF)? (Chọn hai)
Tương tác trước dự án (Pre-engagement interactions)
Xác định lỗ hổng (Vulnerability identification)
16. Hai giai đoạn nào thuộc Hướng dẫn kiểm tra bảo mật nguồn mở (OSSTMM)? (Chọn hai)
Phân tích lỗ hổng (Vulnerability Analysis)
Phân tích niềm tin (Trust Analysis)
Giải thích: OSSTMM gồm các phần: Phân tích niềm tin, Lưu đồ công việc, Kiểm tra bảo mật vật lý, Kiểm tra bảo mật mạng dữ liệu, và Báo cáo với Báo cáo kiểm tra bảo mật (STAR).
17. Phương pháp kiểm tra thâm nhập nào là hướng dẫn toàn diện tập trung vào kiểm tra ứng dụng web? => OWASP WSTG.
18. Hệ điều hành Linux nào bao gồm các công cụ và tài nguyên kiểm tra thâm nhập? => BlackArch.
19. Địa chỉ URL Linux nào cung cấp môi trường học tập thuận tiện về các công cụ và phương pháp kiểm tra bảo mật? => parrotsec.org.
20. Yêu cầu "Giám sát sức khỏe (Health Monitoring)" có ý nghĩa gì khi thiết lập môi trường kiểm tra thâm nhập? => Người kiểm tra cần xác định nguyên nhân khi có sự cố xảy ra.
21. Công cụ nào hữu ích khi thực hiện kiểm tra thâm nhập cơ sở hạ tầng mạng? => Công cụ vượt qua firewall và hệ thống ngăn chặn xâm nhập (IPS).
22. Công cụ nào nên được sử dụng để thực hiện kiểm tra thâm nhập dựa trên ứng dụng? => Công cụ proxy đánh chặn.
23. Công cụ nào nên được sử dụng để kiểm tra thâm nhập hạ tầng không dây? => Công cụ vô hiệu hóa thiết bị mạng.
24. Công cụ nào nên được sử dụng để kiểm tra các nền tảng máy chủ và khách hàng trong môi trường? => Công cụ quét lỗ hổng.
25. Nếu một hệ thống không thể được ảo hóa để kiểm tra thâm nhập đúng cách, hành động nào nên được thực hiện? => Sao lưu toàn bộ hệ thống.

# Chương 2

1. Một nhà thầu được thuê để thực hiện đánh giá lỗ hổng an ninh mạng tại một cơ sở khám chữa bệnh địa phương. Quy định của chính phủ Mỹ nào nhà thầu phải hiểu trước khi bắt đầu? => HIPAA
2. Văn phòng IRS tại New York đang cân nhắc chuyển một số dịch vụ lên nền tảng điện toán đám mây. Quy định nào của chính phủ Mỹ họ cần tuân theo? => FedRAMP
3. Một đại học ở California dự định cung cấp các khóa học trực tuyến cho các sinh viên ở Pháp và Đức. Quy định nào cần tuân thủ? => GDPR
4. Cơ quan nào chịu trách nhiệm thực thi Quy tắc Bảo mật Thông tin Tài chính của Đạo luật GLB? => Ủy ban Thương mại Liên bang (FTC)
5. Trong lĩnh vực y tế, thuật ngữ nào mô tả một đơn vị xử lý thông tin y tế không tiêu chuẩn thành định dạng tiêu chuẩn? => Healthcare Clearinghouse
6. Thuật ngữ nào dùng để chỉ một đơn vị cung cấp thanh toán cho các dịch vụ y tế? => Health Plan
7. Trong thương mại điện tử, yếu tố nào quyết định việc áp dụng các yêu cầu PCI DSS? => Số tài khoản chính (Primary Account Number - PAN)
8. Hai ví dụ về dữ liệu xác thực nhạy cảm liên quan đến thẻ thanh toán cần tuân thủ PCI DSS là gì? => Dữ liệu đầy đủ từ dải từ hoặc dữ liệu tương đương trên chip, Mã CAV2/CVC2/CVV2/CID.
9. Ghép các phần trong NIST SP 800-57 với mô tả tương ứng:
Phần 1: Hướng dẫn chung: Cung cấp hướng dẫn và thực hành tốt nhất về quản lý khóa mã hóa.
Phần 2: Thực hành tốt nhất cho tổ chức quản lý khóa: Cung cấp hướng dẫn về chính sách và yêu cầu lập kế hoạch bảo mật.
Phần 3: Hướng dẫn quản lý khóa theo ứng dụng: Cung cấp hướng dẫn sử dụng các tính năng mã hóa trong hệ thống hiện tại.
10. Nhân viên được giao nhiệm vụ đánh giá hệ thống của các tổ chức tài chính tại châu Âu cần có gì trước khi thực hiện? => Tài liệu cho phép thực hiện kiểm tra từ các tổ chức khách hàng.
11. Công ty thuê chuyên gia an ninh mạng để kiểm tra thâm nhập. Tài liệu pháp lý nào quy định kỳ vọng, hạn chế, thời gian và chi phí? => Service-Level Agreement (SLA).
12. Tài liệu nào mô tả các công việc cụ thể cần thực hiện trong kiểm tra thâm nhập? => Statement of Work (SOW).
13. Công ty muốn đảm bảo rằng nhà tư vấn không tiết lộ thông tin cho bên thứ ba. Loại thỏa thuận NDA nào nên áp dụng? => Unilateral NDA.
Giải thích: Đây là thỏa thuận trong đó một bên cung cấp thông tin và bên kia cam kết không tiết lộ.
14. Công ty thuê chuyên gia an ninh mạng thực hiện kiểm tra thâm nhập để đánh giá tuân thủ quy định của chính phủ. Tài liệu nào phải được cung cấp cho chuyên gia để chỉ định thỏa thuận giữa hai bên? => Hợp đồng (Contract).
15. Khi chuẩn bị báo cáo cuối cùng, phần nào của báo cáo nên nêu rõ các giới hạn của công việc đã thực hiện? => Phần từ chối trách nhiệm (Disclaimers).
16. Ba ví dụ về các yếu tố thông thường trong tài liệu Quy tắc Tham gia (Rules of Engagement) là gì?
Thời gian kiểm tra (Testing Timeline).
Vị trí kiểm tra (Location of Testing).
Phương pháp liên lạc ưa thích (Preferred Method of Communication).
17. Yếu tố nào trong tài liệu Quy tắc Tham gia quy định các bài kiểm tra được phép hoặc không được phép? => Loại kiểm tra được phép hoặc không được phép (Types of Allowed or Disallowed Tests).
18. Tài liệu nào cung cấp thông tin về ngôn ngữ XML dùng để mô tả chức năng của dịch vụ web? => Web Services Description Language (WSDL) Document.
19. Tài liệu nào cung cấp thông tin về ngôn ngữ truy vấn cho APIs và thực thi truy vấn ở thời gian thực? => GraphQL Documentation.
20. Tài liệu nào giúp nhà tư vấn định nghĩa và tài liệu hóa các hệ thống trong phạm vi kiểm tra? => Sơ đồ kiến trúc hệ thống và mạng (System and Network Architectural Diagram).
21. Nguyên nhân nào dẫn đến sự mở rộng không kiểm soát của phạm vi công việc (Scope Creep)? => Nhận diện không hiệu quả các yếu tố kỹ thuật và phi kỹ thuật cần thiết.
22. Bước đầu tiên của nhà tư vấn trong việc xác nhận phạm vi công việc là gì? => Hỏi người liên hệ của công ty và xem xét hợp đồng.
23. Hai giao thức nào nên được xem xét để trao đổi email an toàn? => PGP (Pretty Good Privacy), S/MIME (Secure/Multipurpose Internet Mail Extensions).
24. Thuật ngữ kiểm tra môi trường chưa biết (Unknown Environment Testing) được mô tả như thế nào? => Nhà tư vấn được cung cấp rất ít thông tin về hệ thống và mạng mục tiêu.
25. Sự khác biệt chính giữa kiểm tra môi trường chưa biết và môi trường đã biết là gì? => Lượng thông tin được cung cấp cho nhà tư vấn.

# Chương 3

1. Hai công cụ nào có thể được sử dụng để thu thập thông tin DNS một cách thụ động? => Recon-ng, Dig
2. Lệnh Linux nào có thể được sử dụng để xác định thông tin kỹ thuật và quản trị của một tên miền trong khi thực hiện thu thập thông tin thụ động? => whois
3. Định dạng nào xác định cách hình ảnh và tệp âm thanh lưu trữ metadata? => Exchangeable Image File Format (Exif).
4. Tại sao chuyên gia kiểm tra thâm nhập chọn thực hiện quét thụ động thay vì quét chủ động? => Để thu thập thông tin mà không bị phát hiện.
5. Khi sử dụng lệnh nmap -sU, loại máy chủ nào được liệt kê? => DNS, SNMP, hoặc DHCP server.
6. Nhược điểm của quét không xác thực (unauthenticated scan) là gì? => Không phát hiện được lỗ hổng của các dịch vụ chạy bên trong mục tiêu.
7. Điều gì cần thiết để thực hiện quét xác thực toàn diện đối với một máy chủ Linux? => Thông tin đăng nhập người dùng với quyền truy cập root-level.
8. Trong trường hợp nào thì thực hiện quét không xác thực? => Khi thông tin đăng nhập người dùng không được cung cấp.
9. Tại sao chuyên gia sử dụng lệnh nmap -sF để quét TCP FIN? => Khi quét TCP SYN bị phát hiện bởi firewall hoặc bộ lọc mạng.
10. Mục đích của việc liệt kê máy chủ (host enumeration) khi bắt đầu kiểm tra thâm nhập là gì? => Xác định tất cả các địa chỉ IP đang hoạt động trong phạm vi kiểm tra.
11. Khi sử dụng lệnh nmap -sF để quét TCP FIN và không có phản hồi từ cổng mục tiêu, điều gì có thể được suy ra? => Cổng đang mở.
Giải thích: Nếu không nhận được phản hồi từ cổng, điều này cho thấy cổng đang mở vì hành vi mặc định là bỏ qua gói FIN.
12. Nhược điểm của quét TCP Connect so với quét TCP SYN trong kiểm tra thâm nhập là gì? => Các gói bổ sung có thể kích hoạt báo động IDS.
13. Khi kiểm tra thâm nhập xác định một lỗ hổng, bước tiếp theo để xác minh lỗ hổng là gì? => Xác định xem lỗ hổng có thể bị khai thác hay không.
14. Tại sao tài nguyên Common Vulnerabilities and Exposures (CVE) lại hữu ích khi điều tra các lỗ hổng được phát hiện trong kiểm tra thâm nhập? => CVE là một sự hợp nhất quốc tế các công cụ và cơ sở dữ liệu an ninh mạng.
15. Mục đích của việc áp dụng Hệ thống chấm điểm lỗ hổng chung (CVSS) cho một lỗ hổng được phát hiện là gì? => Tính toán mức độ nghiêm trọng của lỗ hổng.
16. Tại sao tác nhân đe dọa lại xem xét các tin tuyển dụng công việc IT và kỹ thuật của tổ chức mục tiêu? => Để thu thập thông tin về phần cứng và phần mềm đang sử dụng.
17. Thu thập thông tin tình báo nguồn mở (OSINT) thường được thực hiện như thế nào trong kiểm tra thâm nhập? => Sử dụng các tìm kiếm công khai trên Internet.
18. Thông tin ban đầu nào có thể thu được khi thực hiện liệt kê người dùng trong kiểm tra thâm nhập? => Danh sách hợp lệ các người dùng.
19. Thông tin nào có thể thu được từ quét chia sẻ mạng trong kiểm tra thâm nhập? => Các hệ thống chia sẻ tệp, thư mục, và máy in trên mạng.
20. Lợi ích của quét xác thực so với quét không xác thực là gì? => Quét xác thực cung cấp hình ảnh chi tiết hơn về bề mặt tấn công của mục tiêu.
21. Ba yếu tố cần xem xét khi lập kế hoạch quét lỗ hổng trên mạng sản xuất là gì?
Thời gian thực hiện quét.
Băng thông mạng có sẵn.
Cấu trúc mạng (Network topology).
22. Làm thế nào để giảm thiểu tác động đến các thiết bị trung gian khi quét lỗ hổng? => Thực hiện quét càng gần mục tiêu càng tốt.
23. Tính năng quan trọng nhất của báo cáo cuối cùng sau kiểm tra thâm nhập là gì? => Báo cáo đưa ra mô tả chính xác về các lỗ hổng.
24. Lợi thế của việc sử dụng mạng Wi-Fi mục tiêu để kiểm tra gói tin là gì? => Không yêu cầu truy cập vật lý vào tòa nhà.
25. Hướng dẫn của NIST Cybersecurity Framework giúp cải thiện an ninh mạng của tổ chức như thế nào? => Khung làm việc cung cấp các tiêu chuẩn và thực hành tốt nhất trong ngành.

### Chương 4

1. Loại mối đe dọa nào cho phép kẻ tấn công lấy thông tin xác thực của khách hàng ngân hàng bằng cách giả mạo trang đăng nhập của tổ chức tài chính? => Malvertising.
2. Tấn công watering hole là gì? => Tấn công khai thác một trang web mà các thành viên của tổ chức mục tiêu thường truy cập.
3. Hành động lấy thông tin từ nạn nhân mà không trực tiếp yêu cầu thông tin đó được gọi là gì? => Elicitation (Gợi mở).
4. Một kẻ tấn công thay đổi tệp host trên máy tính của nạn nhân, chuyển hướng người dùng đến một trang web độc hại. Đây là loại tấn công gì? => Pharming.
5. Tại sao kẻ tấn công sử dụng Social-Engineering Toolkit (SET)? => Để gửi email spear phishing.
6. Công cụ quản lý VOIP nào có thể giả mạo số ID của người gọi? => Asterisk.
7. Một nhân viên bán hàng cố thuyết phục khách hàng mua sản phẩm vì nguồn cung cấp hạn chế. Phương pháp tác động xã hội nào đang được sử dụng? => Scarcity (Sự khan hiếm).
8. Khi một người nổi tiếng quảng bá sản phẩm trên mạng xã hội, phương pháp tác động xã hội nào được sử dụng? => Social Proof (Bằng chứng xã hội).
9. Apple sử dụng phương pháp tác động xã hội nào khi xây dựng hình ảnh thân thiện với môi trường? => Likeness (Sự yêu thích).
10. Kẻ tấn công gửi email phishing yêu cầu nạn nhân thay đổi mật khẩu ngân hàng ngay lập tức. Phương pháp tác động xã hội nào được sử dụng? => Urgency (Sự cấp bách).
11. Phát biểu nào về tấn công vật lý kỹ thuật xã hội là đúng? => Trong tấn công piggybacking, người không được phép đi theo người được phép vào khu vực hạn chế, thường có sự đồng ý của họ.
12. Công cụ nào cung cấp giao diện web để thao túng người dùng là nạn nhân của tấn công XSS? => BeEF.
13. Công cụ Apple iOS và Android nào có thể giả mạo số điện thoại? => SpoofApp.
14. Hai loại tấn công vật lý nào có thể được giảm thiểu bằng cách sử dụng cửa ra vào kiểm soát truy cập (access control vestibules)? => Tailgating, Piggybacking.
15. Hai tùy chọn kiểm soát truy cập nào thường được sử dụng kết hợp với cửa kiểm soát truy cập? => Thẻ gần (Proximity card) và mã PIN, Quét sinh trắc học (Biometric scan).
16. Nguồn lực nào có thể giảm thiểu tấn công piggybacking và tailgating? => Bảo vệ an ninh (Security guard).
17. Công cụ nào có thể thực hiện các cuộc tấn công kỹ thuật xã hội và tích hợp với các công cụ như Metasploit? => SET (Social-Engineer Toolkit).
18. Ai là mục tiêu của tấn công whaling? => Các nhà quản lý cấp cao như CEO hoặc cá nhân quan trọng trong tổ chức.
19. Mục đích của tấn công vishing là gì? => Thuyết phục nạn nhân qua điện thoại tiết lộ thông tin cá nhân hoặc tài chính.
20. Công cụ nào trên iOS và Android có thể giả mạo số điện thoại, ghi âm cuộc gọi, và tạo tiếng ồn nền? => SpoofCard.
21. Kẻ tấn công gửi tin nhắn SMS yêu cầu nạn nhân nhấp vào liên kết để nhận Bitcoin và nhập thông tin tài khoản ngân hàng. Đây là kiểu tấn công nào? => SMS phishing.
22. Công cụ nào cho phép thực hiện các hoạt động hậu khai thác như Windows reverse VNC DLL hoặc reverse TCP shell? => SET (Social-Engineer Toolkit).
23. Công cụ nào có thể gửi thông báo giả đến trình duyệt của nạn nhân? => BeEF (Browser Exploitation Framework).
24. Một nhân viên mới đăng hình ảnh thẻ nhân viên của mình lên mạng xã hội. Loại tấn công vật lý nào có thể xảy ra? => Badge cloning (Nhân bản thẻ).
25. Một người dùng nhặt được USB trong bãi đỗ xe công ty. Họ nên làm gì với USB này? => Giao USB cho bộ phận bảo mật của công ty.
    
Chương 5 Quiz – Giới thiệu về Ethical Hacking và Penetration Testing

1. Dịch vụ NetBIOS nào được sử dụng cho giao tiếp có kết nối? => NetBIOS-SSN.
2. Ghép cổng với dịch vụ giao thức NetBIOS tương ứng:
UDP port 138: NetBIOS Datagram Service.
UDP port 137: NetBIOS Name Service.
TCP port 445: Giao thức SMB.
TCP port 139: NetBIOS Session Service.
TCP port 135: Microsoft Remote Procedure Call (MS-RPC).
3. Hai tính năng nào trên DNS servers sử dụng BIND 9.5.0 trở lên giúp giảm thiểu tấn công DNS cache poisoning?
Ngẫu nhiên hóa cổng (randomization of ports).
Cung cấp mã hóa bảo mật cho các ID giao dịch DNS (cryptographically secure DNS transaction identifiers).
4. Cổng UDP nào được sử dụng bởi giao thức SNMP? => 161.
5. Đặc điểm của tấn công DNS poisoning là gì? => Thao túng bộ nhớ đệm của bộ phân giải DNS (DNS resolver cache).
6. Công cụ hoặc script nào của Kali Linux có thể thu thập thông tin về thiết bị cấu hình SNMP? => snmp-check.
7. Ghép lệnh SMTP với mô tả tương ứng:
MAIL: Chỉ định địa chỉ email của người gửi.
RSET: Hủy giao dịch email.
EHELO: Khởi tạo giao tiếp với máy chủ SMTP mở rộng.
DATA: Bắt đầu chuyển nội dung của email.
STARTTLS: Bắt đầu kết nối bảo mật TLS với máy chủ email.
HELO: Khởi tạo giao tiếp SMTP với máy chủ email.
8. Hai cách tốt nhất để giảm thiểu lạm dụng và tấn công máy chủ FTP là gì? => Yêu cầu xác thực lại các phiên không hoạt động (re-authentication of inactive sessions), Sử dụng mã hóa dữ liệu khi lưu trữ (encryption at rest).
9. Đặc điểm của tấn công pass-the-hash là gì? => Sử dụng giá trị băm (hash) mật khẩu đã thu thập để xác thực và truy cập các hệ thống khác.
10. Tấn công Kerberoasting là gì? => Hoạt động hậu khai thác nhằm trích xuất băm thông tin đăng nhập của tài khoản dịch vụ từ Active Directory để giải mã ngoại tuyến.
11. Ghép loại tấn công với mô tả tương ứng:
Reflected DOS: Tấn công dùng gói tin giả mạo từ nạn nhân, buộc nguồn gửi phản hồi về nạn nhân.
DNS Amplification: Tấn công khai thác lỗ hổng để biến truy vấn nhỏ thành payload lớn nhằm làm tê liệt máy chủ.
Direct DOS: Nguồn tấn công trực tiếp gửi gói tin đến nạn nhân.
DDOS: Tấn công sử dụng botnet điều khiển từ hệ thống CnC.
12. Ghép loại tấn công với mô tả tương ứng:
Route Manipulation: Tấn công BGP bằng cách cấu hình hoặc chiếm quyền điều khiển router biên.
Downgrade: Buộc hệ thống sử dụng giao thức mã hóa yếu hoặc thuật toán dễ bị tấn công.
DHCP Starvation: Gửi nhiều gói DISCOVER giả mạo làm cạn kiệt địa chỉ IP.
VLAN Hopping: Bỏ qua giới hạn lớp 2 để truy cập trái phép.
MAC Spoofing: Giả mạo địa chỉ vật lý để truy cập trái phép hoặc tấn công man-in-the-middle.
13. Công cụ nào có thể thực hiện tấn công Disassociation? => Airmon-ng.
14. Đặc điểm của tấn công Bluesnarfing là gì? => Tấn công được thực hiện qua Bluetooth với các thiết bị dễ bị tấn công trong phạm vi và lấy cắp thông tin từ thiết bị của nạn nhân.
15. Giao thức Wi-Fi nào dễ bị tấn công brute-force nhất khi triển khai mạng không dây? => WPS (Wi-Fi Protected Setup).
16. Tính năng MFP trong tiêu chuẩn 802.11w giúp bảo vệ chống lại tấn công không dây nào? => Tấn công deauthentication.
17. DNS resolver cache trên hệ thống Windows là gì? => Một cơ sở dữ liệu tạm thời lưu trữ các bản ghi của các trang web đã truy cập gần đây và các lần cố gắng truy cập.
18. Ghép số cổng TCP với giao thức email tương ứng:
465: SMTP over SSL (SMTPS).
587: Secure SMTP (SSMTP) với STARTTLS.
143: IMAP không mã hóa.
995: POP3 mã hóa.
993: IMAP mã hóa.
19. Cổng TCP mặc định nào được sử dụng trong SMTP không mã hóa? => 25.
20. Đặc điểm của tấn công Kerberos Silver Ticket là gì? => Sử dụng vé dịch vụ giả mạo cho một dịch vụ cụ thể trên máy chủ.
21. Tấn công nào là hoạt động hậu khai thác nhằm trích xuất băm thông tin đăng nhập tài khoản dịch vụ từ Active Directory? => Kerberoasting.
22. Bốn yếu tố nào cần thiết để tạo Silver Ticket trong tấn công Kerberos Silver Ticket? => Hash value. ,System account. ,SID. , FQDN (Fully Qualified Domain Name).
23. Tấn công giả mạo IP là loại tấn công nào? => On-path.
24. Thực hành giảm thiểu phổ biến nào cho tấn công ARP cache poisoning trên switch? => DAI (Dynamic ARP Inspection).
25. Kẻ tấn công thực hiện tấn công DDoS phản xạ (reflected DDoS) với lưu lượng phản hồi lớn hơn nhiều so với gói tin ban đầu. Đây là loại tấn công nào? => Amplification (Khuếch đại).

# Chương 6

1. Hai chức năng nào được cung cấp bởi thiết bị proxy web? => Caching các thông điệp HTTP, Cho phép truyền tải HTTP qua tường lửa.
2. Ghép mã trạng thái HTTP trong phản hồi của máy chủ web với mô tả tương ứng.
Mã trạng thái 200: Liên quan đến giao dịch thành công.
Mã trạng thái 300: Liên quan đến việc chuyển hướng HTTP.
Mã trạng thái 400: Liên quan đến lỗi của khách hàng.
Mã trạng thái 500: Liên quan đến lỗi của máy chủ.
Mã trạng thái 100: Thông tin.
3. Ghép các yếu tố trong URL ftp://xyz-company.com:2457/support/file;id=65?name=intro&r=true với mô tả tương ứng.
xyz-company.com: Host.
2457: Port.
support/file: Path.
ftp: Scheme.
name=intro&r=true: Query-string.
id=65: Path-segment-params.
4. Chức năng nào được HTTP 2.0 cung cấp để cải thiện hiệu suất so với HTTP 1.1? => HTTP 2.0 cung cấp multiplexing thông điệp HTTP và yêu cầu ít thông điệp hơn để tải nội dung web.
5. Tại sao các nhà phát triển ứng dụng nên thay đổi tên session ID được sử dụng bởi các framework phát triển ứng dụng web phổ biến? => Các tên session ID này có thể được sử dụng để xác định framework ứng dụng đã được sử dụng.
6. Một người dùng đang sử dụng trang web mua sắm trực tuyến để đặt mua laptop. Cơ chế nào được trang web sử dụng để duy trì xác thực người dùng một cách an toàn trong quá trình mua sắm? => Session ID.
7. Cách tốt nhất để giảm thiểu tấn công session fixation là gì? => Đảm bảo session ID được sử dụng chỉ sau khi người dùng hoàn thành xác thực.
8. Hai thuộc tính nào có thể được thiết lập trong cookie của ứng dụng web để chỉ ra đó là cookie cố định (persistent cookie)? => Expires, Max-Age.
9. Tổ chức quốc tế nào chuyên giáo dục các chuyên gia trong ngành, tạo công cụ và thúc đẩy các phương pháp bảo mật tốt nhất cho các ứng dụng web và hệ thống cơ sở hạ tầng? => Open Web Application Security Project (OWASP).
10. Thành phần nào trong câu lệnh dưới đây có khả năng là thông tin đầu vào từ người dùng trong biểu mẫu web? => a-type.
11. Mô tả nào dưới đây là một ví dụ của tấn công SQL injection theo kiểu out-of-band? => Kẻ tấn công gửi yêu cầu SQL và nhận kết quả qua một kênh khác, ví dụ như qua email.
12. Một kẻ tấn công thực hiện tấn công SQL injection trên một trang web bằng cách gửi nhiều câu lệnh SQL cụ thể để tái tạo thông tin cần thiết. Đây là kiểu tấn công SQL injection nào? => Blind SQL injection.
13. Kẻ tấn công thực hiện tấn công SQL injection trên ứng dụng web bằng cách cố gắng buộc ứng dụng yêu cầu cơ sở dữ liệu backend thực hiện nhiều truy vấn SELECT. Kỹ thuật nào khai thác lỗ hổng SQL injection trên ứng dụng web? => Union operator (Toán tử Union).
14. Truy vấn SQL nào trong câu lệnh SQL select * from users where user = "admin"; là gì? => Static query (Truy vấn tĩnh).
15. Một công ty sử dụng dịch vụ Microsoft Active Directory để quản lý xác thực và phân quyền cho các máy trạm nhân viên. Công ty thuê một chuyên gia bảo mật để thực hiện kiểm tra thâm nhập tuân thủ. Loại kiểm tra thâm nhập nào có thể được sử dụng để xác minh cấu hình đúng của dịch vụ Active Directory? => LDAP injection.
16. Cái nào là thực hành quản lý phiên web nguy hiểm? => Bao gồm session ID trong URL.
17. Một ứng dụng web cấu hình cookie của client với cờ HTTPOnly. Cờ này có tác dụng gì? => Buộc trình duyệt web chỉ xử lý cookie này bởi máy chủ.
18. Một tổ chức đã phát triển chính sách bảo mật mạng yêu cầu các router và switch mới mua phải được cấu hình với các biện pháp bảo mật tiên tiến trước khi triển khai vào mạng sản xuất. Mối đe dọa nào mà chính sách này giảm thiểu? => Tấn công với mật khẩu mặc định.
19. Kẻ tấn công gửi một yêu cầu đến một cổng trường đại học trực tuyến với thông tin: SELECT * FROM group WHERE attack = 'network' AND a-type LIKE 'ping%'; Kẻ tấn công cố khai thác lỗ hổng loại nào? => HTTP parameter pollution (Ô nhiễm tham số HTTP).
20. Một công ty thuê một công ty bảo mật để đánh giá bảo mật của máy chủ web. Để kiểm tra các lỗ hổng cross-site scripting (XSS), tester sẽ sử dụng chuỗi nào? => Trong một trường nhập liệu người dùng trong biểu mẫu web.
21. Theo OWASP, ba quy tắc nào là cần thiết để ngăn ngừa tấn công XSS?
Sử dụng mã hóa HTML trước khi chèn dữ liệu không đáng tin cậy vào nội dung thẻ HTML.
Sử dụng mã hóa thuộc tính trước khi chèn dữ liệu không đáng tin cậy vào thuộc tính HTML.
Sử dụng mã hóa JavaScript trước khi chèn dữ liệu không đáng tin cậy vào các giá trị dữ liệu JavaScript.
22. Sau một số nỗ lực do thám, kẻ tấn công xác định được một máy chủ web được lưu trữ trên hệ thống Linux. Kẻ tấn công nhập URL sau đây: http://192.168.46.82:45/vulnerabilities/fi/?page=../../../../../etc/httpd/httpd.conf. Loại lỗ hổng web nào đang bị khai thác? => Directory traversal (Dò tìm thư mục).
23. Kẻ tấn công nhập URL sau đây để khai thác lỗ hổng trong một ứng dụng web: http://192.168.47.8:76/files/fi/?page=http://malicious.h4cker.org/cookie.html. Loại lỗ hổng nào mà kẻ tấn công cố khai thác =>Remote file inclusion (RFI) - Bao gồm tệp từ xa.
24. Do một thực hành mã hóa không an toàn, kẻ tấn công có thể khai thác và hoàn toàn xâm nhập vào ứng dụng hoặc hệ thống cơ sở hạ tầng. Thực hành mã hóa không an toàn nào đã tạo ra mối đe dọa này? => Sử dụng mật khẩu cứng (hard-coded credentials).
25. Quy tắc tốt nhất để giảm thiểu lỗ hổng do thiếu xử lý lỗi đúng cách trong một ứng dụng là gì? => Sử dụng một bộ thông báo lỗi hợp lý cung cấp thông tin có ý nghĩa cho người dùng nhưng không cung cấp thông tin hữu ích cho kẻ tấn công.

# Chương 7:

1. Thuật ngữ nào là đặc điểm thiết yếu của điện toán đám mây theo định nghĩa trong NIST SP 800-145?
•	Resource pooling (Tích hợp tài nguyên).
Giải thích: NIST SP 800-145 định nghĩa điện toán đám mây là "mô hình cho phép truy cập mạng thuận tiện, theo yêu cầu vào một nhóm tài nguyên tính toán có thể cấu hình mà có thể được cấp phát và giải phóng nhanh chóng với ít nỗ lực quản lý hoặc tương tác với nhà cung cấp dịch vụ." Các đặc điểm thiết yếu của điện toán đám mây bao gồm:
•	Dịch vụ tự phục vụ theo yêu cầu.
•	Truy cập mạng rộng.
•	Tích hợp tài nguyên.
•	Tính đàn hồi nhanh chóng.
•	Dịch vụ có đo lường.
________________________________________
2. Phương pháp tấn công công nghệ đám mây nào liên quan đến việc xâm nhập vào hạ tầng để thu thập và đánh cắp thông tin như tên người dùng hợp lệ, mật khẩu, mã thông báo và mã PIN?
•	Credential harvesting (Thu thập thông tin xác thực).
Giải thích: Credential harvesting là hành động thu thập và đánh cắp thông tin xác thực như tên người dùng, mật khẩu, mã thông báo, mã PIN và các thông tin xác thực khác qua việc xâm nhập vào hạ tầng.
________________________________________
3. Phương pháp tấn công công nghệ đám mây nào có thể khai thác lỗi trong ứng dụng phần mềm để có quyền truy cập vào các tài nguyên vốn dĩ không thể truy cập đối với người dùng?
•	Privilege escalation (Nâng cao quyền hạn).
Giải thích: Privilege escalation khai thác lỗi hoặc điểm yếu trong phần mềm hoặc ứng dụng phần mềm để truy cập các tài nguyên mà lẽ ra người dùng không được phép truy cập.
________________________________________
4. Thuật ngữ nào mô tả khi một người dùng có quyền thấp hơn truy cập các chức năng dành riêng cho người dùng có quyền cao hơn?
•	Vertical privilege escalation (Nâng cao quyền hạn theo chiều dọc).
Giải thích: Vertical privilege escalation xảy ra khi một người dùng có quyền thấp truy cập các chức năng dành cho người dùng có quyền cao hơn, ví dụ như người dùng tiêu chuẩn truy cập các chức năng của quản trị viên.
________________________________________
5. Phương pháp tấn công công nghệ đám mây nào kẻ tấn công có thể sử dụng để truy cập vào tài khoản người dùng hoặc ứng dụng cho phép truy cập vào nhiều tài khoản và thông tin hơn?
•	Account takeover (Chiếm quyền tài khoản).
Giải thích: Trong tấn công account takeover, kẻ tấn công chiếm quyền truy cập vào tài khoản người dùng hoặc ứng dụng và sử dụng nó để truy cập vào nhiều tài khoản và thông tin hơn.
________________________________________
6. Công cụ nào có thể được sử dụng để tìm các lỗ hổng có thể dẫn đến tấn công dịch vụ metadata?
•	Nimbostratus.
Giải thích: Công cụ như Nimbostratus (https://github.com/andresriancho/nimbostratus) có thể được sử dụng để tìm các lỗ hổng có thể dẫn đến tấn công dịch vụ metadata.
________________________________________
7. Phương pháp tấn công công nghệ đám mây nào có thể tạo các gói tin giả để khiến một ứng dụng đám mây bị sập?
•	Resource exhaustion attack (Tấn công cạn kiệt tài nguyên).
Giải thích: Kẻ tấn công có thể thực hiện các tấn công DoS chiến lược chống lại các ứng dụng được lưu trữ trong đám mây, gây cạn kiệt tài nguyên và làm cho ứng dụng bị sập.
________________________________________
8. Phương pháp tấn công công nghệ đám mây nào yêu cầu kẻ tấn công tạo ra một ứng dụng độc hại và cài đặt nó vào môi trường SaaS, PaaS hoặc IaaS?
•	Cloud malware injection attack (Tấn công tiêm mã độc vào đám mây).
Giải thích: Trong một tấn công cloud malware injection, kẻ tấn công tạo ra một ứng dụng độc hại và tiêm vào môi trường SaaS, PaaS hoặc IaaS. Sau khi tiêm mã độc thành công, mã độc này sẽ được thực thi như một trong các instance hợp lệ chạy trong hạ tầng đám mây.
________________________________________
9. Nguyên nhân phổ biến nào gây ra vi phạm dữ liệu trong các cuộc tấn công vào tài sản đám mây cấu hình sai?
•	Sử dụng cấu hình quyền truy cập không an toàn cho các dịch vụ lưu trữ đối tượng đám mây.
Giải thích: Vi phạm dữ liệu thường xảy ra do các cấu hình quyền truy cập không an toàn cho các dịch vụ lưu trữ đối tượng đám mây, như các bucket AWS S3 của Amazon.
________________________________________
10. Một kẻ tấn công đã xâm nhập vào một VM trong môi trường đám mây chia sẻ phần cứng vật lý với các VM chưa bị xâm nhập. Phương pháp tấn công công nghệ đám mây nào có thể được sử dụng để trích xuất thông tin nhạy cảm như mật khẩu, khóa mã hóa và thông tin nhạy cảm khác?
•	Side-channel attack (Tấn công kênh phụ).
Giải thích: Tấn công kênh phụ dựa trên thông tin thu được từ việc triển khai hệ thống máy tính hoặc môi trường đám mây thay vì khai thác điểm yếu cụ thể trong công nghệ hoặc thuật toán đã triển khai.
________________________________________
11. Công cụ nào giúp các nhà phát triển phần mềm và người tiêu dùng đám mây triển khai ứng dụng trong đám mây và sử dụng các tài nguyên mà nhà cung cấp đám mây cung cấp?
•	Cloud development kits (CDKs).
Giải thích: Cloud development kits (CDKs) giúp các nhà phát triển phần mềm và người tiêu dùng đám mây triển khai ứng dụng trong đám mây và sử dụng các tài nguyên mà nhà cung cấp đám mây cung cấp.
________________________________________
12. Lỗ hổng nào của thiết bị di động bị nhắm đến khi kẻ tấn công phân tích mã ngược một ứng dụng di động để xem cách thức tạo và lưu trữ các khóa trong iOS Keychain?
•	Insecure storage (Lưu trữ không an toàn).
Giải thích: Kẻ tấn công có thể sử dụng phân tích tĩnh hoặc phân tích mã ngược để xem cách các ứng dụng tạo và lưu trữ khóa trong iOS Keychain.
13. Công cụ nào là một framework mã nguồn mở được sử dụng để kiểm tra bảo mật của các ứng dụng iOS?
•	Needle
Giải thích: Needle là một framework mã nguồn mở được sử dụng để kiểm tra bảo mật của các ứng dụng iOS. Drozer, APK Studio và ApkX là các công cụ kiểm tra dành cho Android.
________________________________________
14. Giai đoạn Bluetooth Low Energy (BLE) nào tương ứng với mô tả sau đây?
Giải thích:
•	Giai đoạn 1: Phân phối khóa đặc thù cho giao thức
•	Giai đoạn 2: Tạo khóa ngắn hạn
•	Giai đoạn 3: Trao đổi tính năng ghép nối
________________________________________
15. Lỗ hổng bảo mật nào ảnh hưởng đến các triển khai IoT?
•	Plaintext communication and data leakage (Giao tiếp dạng văn bản rõ và rò rỉ dữ liệu).
Giải thích: Các lỗ hổng bảo mật IoT phổ biến bao gồm:
•	Cấu hình mặc định không an toàn.
•	Giao tiếp dạng văn bản rõ và rò rỉ dữ liệu.
•	Cấu hình cứng.
•	Phần mềm/ phần cứng lỗi thời và sử dụng các thành phần không an toàn hoặc lỗi thời.
________________________________________
16. Hai hệ thống IoT nào không bao giờ nên được kết nối Internet? (Chọn hai.)
•	Turbines in a power plant (Tua-bin trong nhà máy điện).
•	Robots in a factory (Robot trong nhà máy).
Giải thích: Nhiều hệ thống IoT, ICS và SCADA không nên kết nối với Internet. Ví dụ: các bộ điều khiển logic lập trình (PLC) điều khiển tua-bin trong nhà máy điện, đèn sân vận động và robot trong nhà máy không nên được kết nối Internet.
________________________________________
17. Thuật ngữ nào mô tả tập hợp các đặc tả giao diện tính toán được thiết kế để cung cấp khả năng quản lý và giám sát độc lập với CPU, firmware và hệ điều hành của máy chủ?
•	Intelligent Platform Management Interface (IPMI).
Giải thích: IPMI là một tập hợp các đặc tả giao diện tính toán (thường được sử dụng bởi các hệ thống IoT) giúp cung cấp khả năng quản lý và giám sát độc lập với CPU, firmware và hệ điều hành của máy chủ.
________________________________________
18. Một kẻ tấn công đã tải một VM có phần mềm độc hại lên VMware Marketplace. Khi một tổ chức triển khai VM này, kẻ tấn công có thể thao túng hệ thống, ứng dụng và dữ liệu người dùng. Loại lỗ hổng VM nào đã được kích hoạt?
•	VM escape vulnerability (Lỗ hổng thoát VM).
Giải thích: Lỗ hổng VM escape cho phép kẻ tấn công "thoát" khỏi VM và truy cập vào các máy ảo khác trong hệ thống hoặc truy cập vào hypervisor.
________________________________________
19. Công cụ nào là bộ công cụ phân tích mã nguồn mở sử dụng công cụ chống virus ClamAV để giúp phát hiện lỗ hổng, Trojans, backdoor và mã độc trong hình ảnh và container Docker?
•	Dagda
Giải thích: Dagda là bộ công cụ phân tích mã nguồn mở có thể giúp phát hiện lỗ hổng, Trojans, backdoor và mã độc trong hình ảnh và container Docker, sử dụng công cụ chống virus ClamAV để phát hiện mã độc và lỗ hổng.
________________________________________
20. Công cụ thu thập thông tin xác thực nào có thể được sử dụng để gửi email spear phishing với liên kết đến một trang web độc hại cho một nạn nhân mục tiêu?
•	Social-Engineer Toolkit (SET).
Giải thích: Social-Engineer Toolkit (SET) có thể thực hiện các cuộc tấn công kỹ thuật xã hội và tạo ra một trang web giả để thực hiện cuộc tấn công thu thập thông tin xác thực.
________________________________________
21. Tại sao các kiến trúc đám mây giúp giảm thiểu tác động của các cuộc tấn công DoS hoặc DDoS so với các dịch vụ lưu trữ tại chỗ?
•	Cloud providers use a distributed architecture (Nhà cung cấp đám mây sử dụng kiến trúc phân tán).
Giải thích: Một trong những lợi ích của việc sử dụng dịch vụ đám mây là kiến trúc phân tán và khả năng phục hồi mà hầu hết các nhà cung cấp đám mây lớn cung cấp. Kiến trúc này giúp giảm thiểu tác động của các cuộc tấn công DoS hoặc DDoS so với khi ứng dụng được lưu trữ tại trung tâm dữ liệu tại chỗ.
________________________________________
22. Thuộc tính nào là đặc điểm của một VM hypervisor?
•	Type 1 hypervisors are also known as native or bare-metal hypervisors (Hypervisor loại 1 còn được gọi là hypervisor gốc hoặc hypervisor phần cứng).
Giải thích: Có hai loại hypervisor:
•	Type 1 hypervisors: (Hypervisor gốc hoặc phần cứng) chạy trực tiếp trên hệ thống vật lý (bare-metal system). Ví dụ bao gồm VMware ESXi, Proxmox Virtual Environment, Xen và Microsoft Hyper-V.
•	Type 2 hypervisors: Chạy trên hệ điều hành khác. Ví dụ bao gồm VirtualBox và VMware Player hoặc Workstation.
________________________________________
23. Một kẻ tấn công đã xâm nhập vào một VM trong trung tâm dữ liệu và phát hiện một lỗ hổng cung cấp quyền truy cập vào dữ liệu trong một VM khác. Loại lỗ hổng VM nào đã được phát hiện?
•	VM escape vulnerability (Lỗ hổng thoát VM).
Giải thích: Lỗ hổng VM escape cho phép kẻ tấn công "thoát" khỏi VM và truy cập vào các máy ảo khác trong hệ thống hoặc truy cập vào hypervisor.
________________________________________
24. Công cụ nào có thể được sử dụng để thực hiện các cuộc tấn công trên đường truyền trong các triển khai BLE?
•	GATTacker
Giải thích: GATTacker là công cụ có thể được sử dụng để thực hiện các cuộc tấn công trên đường truyền trong các triển khai Bluetooth Low Energy (BLE).
________________________________________
25. Công cụ nào là bộ quét lỗ hổng container mã nguồn mở có thể được sử dụng để tìm các lỗ hổng trong hình ảnh Docker?
•	Anchore’s Grype
Giải thích: Anchore’s Grype là công cụ quét lỗ hổng container mã nguồn mở có thể được sử dụng để tìm các lỗ hổng trong hình ảnh Docker.
Chương 8 Quiz – Giới thiệu về Ethical Hacking và Penetration Testing
1. Tài nguyên nào là một tiện ích của Windows kết hợp chức năng của CMD cũ với một bộ lệnh mới cho scripting/cmdlet cùng với các chức năng quản trị hệ thống tích hợp?
•	PowerShell Giải thích: Windows PowerShell là một shell mới của Microsoft kết hợp chức năng của command prompt (CMD) cũ với một bộ lệnh mới cho scripting/cmdlet, cung cấp các chức năng quản trị hệ thống tích hợp. PowerShell cmdlets cho phép người dùng và quản trị viên tự động hóa các tác vụ phức tạp bằng các script có thể tái sử dụng.
________________________________________
2. Tham chiếu đến hình minh họa. Một kẻ tấn công mở một cổng hoặc trình nghe trên hệ thống bị xâm nhập và chờ kết nối. Mục tiêu là kết nối với nạn nhân từ bất kỳ hệ thống nào, thực thi các lệnh và thao túng thêm nạn nhân. Loại hoạt động độc hại nào đang được thực hiện?

•	Reverse shell Giải thích: Với reverse shell, kẻ tấn công mở một cổng hoặc trình nghe trên hệ thống bị xâm nhập và chờ kết nối. Sau đó, kẻ tấn công có thể kết nối với nạn nhân từ bất kỳ hệ thống nào, thực thi lệnh và thao túng thêm hệ thống của nạn nhân.
________________________________________
3. Tài nguyên nào là một công cụ nhẹ và di động cho phép tạo bind và reverse shell từ một máy chủ bị xâm nhập?
•	Netcat Giải thích: Netcat là một trong những công cụ phổ biến và linh hoạt nhất trong kiểm tra bảo mật. Nó rất nhẹ và di động, cho phép tạo các kết nối bind và reverse shell từ một máy chủ bị xâm nhập.
________________________________________
4. Một sinh viên an ninh mạng đang học các lệnh Netcat có thể được sử dụng trong một cuộc kiểm tra thâm nhập. Lệnh Netcat nào được sử dụng để kết nối với cổng TCP?
•	nc -nv Giải thích: Lệnh nc -nv được sử dụng để kết nối với một cổng TCP. Các lệnh khác như nc -lvp được sử dụng để lắng nghe trên một cổng TCP.
________________________________________
5. Lệnh Meterpreter nào được sử dụng để thực thi các lệnh Meterpreter được liệt kê trong một tệp văn bản và giúp tăng tốc các hành động thực hiện trên hệ thống của nạn nhân?
•	resource Giải thích: Lệnh resource trong Meterpreter được sử dụng để thực thi các lệnh Meterpreter đã được liệt kê trong tệp văn bản, giúp tăng tốc quá trình thực hiện các hành động trên hệ thống của nạn nhân.
________________________________________
6. Hai tài nguyên nào là công cụ C2 (Command and Control)? (Chọn hai)
•	Socat
•	Twittor Giải thích: Socat và Twittor là các công cụ C2, cho phép tạo các kênh giao tiếp và thực hiện các cuộc tấn công mạng từ xa. Netcat và BloodHound không phải là công cụ C2.
________________________________________
7. Loại kênh nào được tạo ra bởi một C2 với một hệ thống đã bị xâm nhập?
•	Covert channel Giải thích: C2 tạo ra một kênh bí mật (covert channel) với hệ thống đã bị xâm nhập. Kênh này cho phép kẻ tấn công truyền tải dữ liệu giữa các quy trình hoặc hệ thống mà chính sách bảo mật của hệ thống không cho phép giao tiếp.
________________________________________
8. Kỹ thuật khai thác nào sử dụng các công cụ sống sót để lấy danh sách thư mục, sao chép và di chuyển tệp, lấy danh sách các tiến trình đang chạy và thực hiện các tác vụ quản trị?
•	PowerShell Giải thích: PowerShell có thể lấy danh sách thư mục, sao chép và di chuyển tệp, lấy danh sách các tiến trình đang chạy và thực hiện các tác vụ quản trị.
________________________________________
9. Tài nguyên nào là một framework mã nguồn mở cho phép triển khai nhanh các module sau khai thác, bao gồm keyloggers, bind và reverse shells, và giao tiếp có thể thích ứng để tránh bị phát hiện?
•	Empire Giải thích: Empire là một framework mã nguồn mở bao gồm các agent PowerShell cho Windows và Python cho Linux. Nó cho phép triển khai nhanh các module sau khai thác như keyloggers, bind và reverse shells.
________________________________________
10. Tài nguyên nào là một ứng dụng web JavaScript trang đơn có thể được sử dụng để tìm các đường tấn công phức tạp trong Microsoft Azure?
•	BloodHound Giải thích: BloodHound là một ứng dụng web JavaScript trang đơn sử dụng lý thuyết đồ thị để khám phá các mối quan hệ ẩn trong môi trường Windows Active Directory. Nó cũng có thể được sử dụng để tìm các đường tấn công phức tạp trong Microsoft Azure.
________________________________________
11. Công cụ nào có thể được sử dụng để viết các script hoặc ứng dụng để tự động hóa các tác vụ quản trị trên máy tính từ xa và cũng có thể được sử dụng bởi phần mềm độc hại để thực hiện các hoạt động khác nhau trong một hệ thống bị xâm nhập?
•	WMI Giải thích: Windows Management Instrumentation (WMI) quản lý dữ liệu và các tác vụ trên hệ điều hành Windows. WMI có thể được sử dụng để viết script tự động hóa các tác vụ quản trị từ xa và có thể được sử dụng bởi phần mềm độc hại để thực hiện các hoạt động trong hệ thống bị xâm nhập.
________________________________________
12. Công cụ Sysinternals nào được sử dụng bởi các kiểm tra thâm nhập để thay đổi các giá trị trong registry của Windows và kết nối hệ thống bị xâm nhập với hệ thống khác?
•	PsExec Giải thích: PsExec là một trong những công cụ mạnh mẽ nhất trong bộ Sysinternals. Nó có thể thực thi bất kỳ lệnh nào có thể chạy trên command prompt của Windows, bao gồm việc thay đổi các giá trị trong registry và kết nối hệ thống bị xâm nhập với hệ thống khác.
•	13. Ba công cụ nào là các kỹ thuật sau khai thác "living-off-the-land"? (Chọn ba)
•	PowerSploit
•	WinRM
•	Empire Giải thích: Các công cụ như PowerSploit, WinRM và Empire là các công cụ giúp thực hiện các kỹ thuật "living-off-the-land", cho phép kẻ tấn công sử dụng các công cụ hệ thống sẵn có để duy trì sự kiểm soát sau khi khai thác thành công. Socat, WMImplant và Twittor là các công cụ C2 (Command and Control).
•	________________________________________
•	14. Kẻ tấn công muốn cho phép kết nối tiếp theo đến một hệ thống bị xâm nhập và duy trì quyền truy cập liên tục. Kẻ tấn công sử dụng lệnh hệ thống Windows Enable-PSRemoting -SkipNetworkProfileCheck –Force. Công cụ nào đang được bật bằng lệnh này?
•	WinRM Giải thích: WinRM (Windows Remote Management) có thể hữu ích cho các hoạt động sau khai thác. Lệnh Enable-PSRemoting -SkipNetworkProfileCheck –Force giúp bật WinRM trên hệ thống Windows, cho phép các kết nối từ xa tiếp theo.
•	________________________________________
•	15. Hoạt động độc hại nào được thực hiện khi một người dùng có quyền hạn thấp truy cập các chức năng chỉ dành cho người dùng có quyền hạn cao hơn?
•	Vertical privilege escalation Giải thích: Vertical privilege escalation là khi một người dùng có quyền hạn thấp truy cập các chức năng được bảo vệ và chỉ dành cho người dùng có quyền hạn cao hơn, ví dụ như truy cập vào các quyền của quản trị viên (root hoặc admin).
•	________________________________________
•	16. Công cụ nào có thể được sử dụng để mã hóa, né tránh và che giấu dấu vết của kẻ tấn công?
•	Steghide Giải thích: Steghide là một công cụ steganography (che giấu thông tin) cho phép ẩn giấu thông điệp hoặc nội dung khác trong các tệp hình ảnh hoặc video. Kẻ tấn công có thể sử dụng công cụ này để mã hóa và che giấu dấu vết của mình.
•	________________________________________
•	17. Sau khi xâm nhập hệ thống trong một cuộc kiểm tra thâm nhập, tất cả công việc thâm nhập nên được dọn dẹp, bao gồm các tệp dư thừa, thay đổi hệ thống và nhật ký đã chỉnh sửa. Phương pháp làm sạch phương tiện (media sanitation) nên được thảo luận với khách hàng và chủ sở hữu hệ thống bị ảnh hưởng. Tài liệu nào hướng dẫn việc làm sạch phương tiện?
•	NIST SP 800-88 Giải thích: NIST Special Publication 800-88, Revision 1: "Guidelines for Media Sanitization" là tài liệu hướng dẫn quy trình làm sạch phương tiện sau khi kết thúc cuộc kiểm tra thâm nhập. Việc làm sạch này đảm bảo rằng không còn dữ liệu nhạy cảm nào tồn tại trên hệ thống.
•	________________________________________
•	18. Quy trình nào nên được triển khai để bảo vệ mạng khỏi việc di chuyển ngang (lateral movement)?
•	VLANs Giải thích: Việc sử dụng VLANs (Virtual Local Area Networks) là một phương pháp hiệu quả để phân đoạn mạng và ngăn chặn di chuyển ngang trong mạng. Các hệ thống phải được phân vùng đúng cách để hạn chế kẻ tấn công di chuyển trong mạng.
•	________________________________________
•	19. Lợi ích chính của Remote Desktop so với Sysinternals là gì?
•	It gives a full, interactive GUI of the remote compromised computer. Giải thích: Remote Desktop cho phép truy cập giao diện đồ họa đầy đủ và tương tác với máy tính từ xa, điều này vượt trội hơn so với các công cụ như Sysinternals, vốn chỉ cung cấp các tính năng quản lý và điều khiển hệ thống từ xa mà không có giao diện đồ họa.
•	________________________________________
•	20. Hệ thống tấn công có một listener (cổng mở), và nạn nhân thực hiện kết nối lại với hệ thống tấn công. Loại lỗ hổng nào được mô tả trong tình huống này?
•	Reverse shell Giải thích: Reverse shell là khi kẻ tấn công có một listener (cổng mở) và hệ thống bị xâm nhập (nạn nhân) thực hiện kết nối lại với kẻ tấn công. Đây là một kỹ thuật phổ biến trong tấn công mạng.
•	________________________________________
•	21. Một sinh viên an ninh mạng đang học các lệnh Netcat có thể được sử dụng trong một cuộc kiểm tra thâm nhập. Sinh viên muốn sử dụng Netcat như một công cụ quét cổng. Lệnh nào cần sử dụng?
•	nc -z Giải thích: Lệnh nc -z được sử dụng để quét các cổng, xác định các cổng mở trên một hệ thống. Đây là một trong các lệnh hữu ích trong quá trình kiểm tra thâm nhập.
•	________________________________________
•	22. Công cụ C2 nào là công cụ dựa trên PowerShell sử dụng WMI để tạo một kênh C2?
•	WMImplant Giải thích: WMImplant là một công cụ C2 dựa trên PowerShell sử dụng Windows Management Instrumentation (WMI) để tạo một kênh C2 cho các hoạt động kiểm soát từ xa.
•	________________________________________
•	23. Hai công cụ C2 nào được phát triển bằng Python? (Chọn hai)
•	TrevorC2
•	Wsc2 Giải thích: TrevorC2 và Wsc2 là các công cụ C2 được phát triển bằng Python. Các công cụ này cung cấp khả năng kiểm soát và điều khiển từ xa các hệ thống bị xâm nhập.
•	________________________________________
•	24. Sau giai đoạn khai thác, cần duy trì một foothold (chỗ đứng) trong hệ thống đã bị xâm nhập để thực hiện các tác vụ bổ sung. Cách nào có thể duy trì sự tồn tại trong hệ thống bị xâm nhập?
•	Creating a bind or reverse shell Giải thích: Sau khi khai thác thành công, việc tạo một bind hoặc reverse shell là một phương pháp phổ biến để duy trì sự tồn tại và kết nối liên tục với hệ thống bị xâm nhập.
•	________________________________________
•	25. Hai lệnh nào là giống nhau giữa Meterpreter và các hệ thống Linux hoặc Unix-based? (Chọn hai)
•	pwd
•	cat Giải thích: Các lệnh Meterpreter giống với các lệnh trong hệ thống Linux hoặc Unix bao gồm pwd (hiển thị thư mục hiện tại) và cat (hiển thị nội dung của tệp).
Chương 9 Quiz – Giới thiệu về Ethical Hacking và Penetration Testing
1. Phương pháp tiêu chuẩn ngành nào đã tạo ra một danh mục các lỗ hổng đã biết và cung cấp một điểm số chỉ ra mức độ nghiêm trọng của lỗ hổng?
•	CVSS Giải thích: CVSS (Common Vulnerability Scoring System) là hệ thống điểm số để đánh giá mức độ nghiêm trọng của các lỗ hổng bảo mật. Nó cung cấp một điểm số từ 0 đến 10 để chỉ ra mức độ nghiêm trọng của lỗ hổng.
________________________________________
2. Danh mục lỗ hổng nào tạo ra danh sách các lỗ hổng công khai đã biết, mỗi lỗ hổng được cấp một ID số, mô tả và tham chiếu?
•	CVE Giải thích: CVE (Common Vulnerabilities and Exposures) là danh sách các lỗ hổng bảo mật công khai đã biết, mỗi lỗ hổng được cấp một ID số duy nhất, mô tả chi tiết và tham chiếu các nguồn liên quan.
________________________________________
3. Khớp nhóm chỉ số CVSS với thông tin tương ứng.
Giải thích:
•	Environmental metric group: Bao gồm các chỉ số cơ sở đã sửa đổi, yêu cầu về tính bảo mật, tính toàn vẹn và tính sẵn có.
•	Base metric group: Bao gồm các chỉ số về khả năng khai thác và tác động.
•	Temporal metric group: Bao gồm độ trưởng thành của mã khai thác, mức độ khắc phục và độ tin cậy của báo cáo.
________________________________________
4. Ba mục nào được bao gồm trong nhóm chỉ số cơ sở được sử dụng bởi CVSS? (Chọn ba)
•	attack complexity
•	integrity impact
•	user interaction Giải thích: Nhóm chỉ số cơ sở của CVSS bao gồm các chỉ số về khả năng khai thác (ví dụ: attack vector, attack complexity, privileges required, user interaction) và các chỉ số về tác động (ví dụ: confidentiality impact, integrity impact, availability impact).
________________________________________
5. Mục nào được bao gồm trong nhóm chỉ số môi trường được sử dụng bởi CVSS?
•	confidentiality requirements Giải thích: Nhóm chỉ số môi trường bao gồm các chỉ số yêu cầu về bảo mật, tính toàn vẹn và tính sẵn có, cũng như các chỉ số về môi trường hệ thống.
________________________________________
6. Mục nào được bao gồm trong nhóm chỉ số tạm thời (temporal) được sử dụng bởi CVSS?
•	exploit code maturity Giải thích: Nhóm chỉ số tạm thời bao gồm các yếu tố như độ trưởng thành của mã khai thác, mức độ khắc phục và độ tin cậy của báo cáo.
________________________________________
7. Công cụ nào có thể nhận kết quả từ nhiều công cụ kiểm tra thâm nhập mà nhà phân tích bảo mật sử dụng và giúp tạo báo cáo ở các định dạng như CSV, HTML và PDF?
•	Dradis Giải thích: Dradis là một công cụ hữu ích giúp nhà phân tích bảo mật tích hợp kết quả từ nhiều công cụ kiểm tra thâm nhập và tạo báo cáo ở các định dạng khác nhau như CSV, HTML, và PDF.
________________________________________
8. Khớp mô tả với nhóm kiểm soát tương ứng.
Giải thích:
•	Key rotation: Kiểm soát kỹ thuật
•	Input sanitization: Kiểm soát kỹ thuật
•	Secure software development life cycle: Kiểm soát hành chính
•	Role-based access control: Kiểm soát hành chính
•	Time-of-day restrictions: Kiểm soát vận hành
•	Job rotation: Kiểm soát vận hành
•	Video surveillance: Kiểm soát vật lý
•	Biometric controls: Kiểm soát vật lý
________________________________________
9. Hai mục nào là ví dụ về các kiểm soát kỹ thuật có thể được khuyến nghị để giảm thiểu và khắc phục các lỗ hổng được phát hiện trong một bài kiểm tra thâm nhập? (Chọn hai)
•	multifactor authentication
•	certificate management Giải thích: Các kiểm soát kỹ thuật sử dụng công nghệ để giảm thiểu các lỗ hổng. Ví dụ bao gồm xác thực đa yếu tố và quản lý chứng chỉ.
________________________________________
10. Báo cáo kiểm tra thâm nhập gần đây bao gồm thông tin về khắc phục cấp độ quy trình, quản lý bản vá và các giải pháp quản lý bí mật. Nhóm kiểm soát nào được đại diện trong ví dụ này?
•	technical Giải thích: Báo cáo này chứa các đề xuất về kiểm soát kỹ thuật, chẳng hạn như khắc phục cấp độ quy trình, quản lý bản vá và giải pháp quản lý bí mật.
________________________________________
11. Tài liệu nào cung cấp các bảng cheat sheet và hướng dẫn chi tiết về cách ngăn ngừa các lỗ hổng như cross-site scripting, SQL injection và command injection?
•	OWASP Giải thích: OWASP (Open Web Application Security Project) cung cấp các bảng cheat sheet và hướng dẫn chi tiết để ngăn ngừa các lỗ hổng như cross-site scripting (XSS), SQL injection và command injection.
________________________________________
12. Báo cáo của nhà phân tích bảo mật nên bao gồm các yêu cầu mật khẩu tối thiểu và các chính sách và thủ tục. Đây là ví dụ của nhóm kiểm soát nào?
•	administrative Giải thích: Các kiểm soát hành chính bao gồm các chính sách, quy tắc và đào tạo nhằm giảm thiểu rủi ro và cải thiện bảo mật. Ví dụ là các yêu cầu mật khẩu tối thiểu và các chính sách và thủ tục.
13. Nhóm kiểm soát nào bao gồm thông tin về kỳ nghỉ bắt buộc và đào tạo người dùng trong báo cáo của nhà phân tích bảo mật?
•	Administrative Giải thích: Các kiểm soát hành chính bao gồm các chính sách, quy tắc và đào tạo nhằm giảm thiểu rủi ro và cải thiện bảo mật. Ví dụ như các kỳ nghỉ bắt buộc và đào tạo người dùng.
________________________________________
14. Khi tạo báo cáo của nhà phân tích bảo mật, nhóm kiểm soát nào bao gồm thông tin liên quan đến kiểm soát vestibule truy cập?
•	Physical Giải thích: Các kiểm soát vật lý sử dụng các biện pháp an ninh để ngăn ngừa hoặc ngăn chặn truy cập trái phép vào các khu vực nhạy cảm hoặc vật liệu. Kiểm soát vestibule truy cập là một ví dụ của kiểm soát vật lý.
________________________________________
15. Khớp thuật ngữ với mô tả tương ứng.
False Negative: Các hoạt động độc hại không được phát hiện bởi thiết bị an ninh mạng.
True Negative: Một thiết bị phát hiện xâm nhập nhận dạng một hoạt động là hành vi chấp nhận được và hoạt động này thực sự là hợp lệ.
False Positive: Một thiết bị bảo mật phát ra cảnh báo, nhưng không có hoạt động độc hại hoặc cuộc tấn công thực tế xảy ra.
True Positive: Xác định chính xác một cuộc tấn công bảo mật hoặc sự kiện độc hại.

16. Loại sự kiện nào còn được gọi là "trình kích hoạt vô hại"?
•	False Positive Giải thích: False positive (cảnh báo giả) còn được gọi là "trình kích hoạt vô hại". Đây là những cảnh báo sai lệch khiến người dùng hiểu nhầm về một mối đe dọa không thực sự tồn tại.
________________________________________
17. Loại sự kiện nào làm giảm giá trị và độ khẩn cấp của các cảnh báo thực sự?
•	False Positives Giải thích: False positives làm giảm giá trị và độ khẩn cấp của các cảnh báo thực sự vì chúng tạo ra các cảnh báo giả, khiến người dùng không thể phân biệt được mối đe dọa thật sự.
________________________________________
18. Loại sự kiện nào là các hoạt động độc hại không được phát hiện bởi thiết bị bảo mật mạng?
•	False Negatives Giải thích: False negatives là các hoạt động độc hại mà thiết bị bảo mật mạng không phát hiện được. Điều này có thể dẫn đến các lỗ hổng bảo mật nghiêm trọng.
19. Loại sự kiện nào xảy ra khi thiết bị phát hiện xâm nhập nhận diện một hoạt động là hành vi chấp nhận được và hoạt động đó thực sự hợp lệ? => True Negatives. 
20. Loại sự kiện nào là việc xác định thành công một cuộc tấn công bảo mật? => True Positive.
21. Ví dụ nào của kiểm soát kỹ thuật được khuyến nghị để giảm thiểu và ngăn ngừa các lỗ hổng như cross-site scripting, cross-site request forgery, SQL injection và command injection? => User input sanitization.
22. Ví dụ nào của kiểm soát hành chính giúp quản lý những gì người dùng có thể làm ở cả cấp độ rộng và chi tiết? => RBAC (Role-Based Access Control)
23. Tài liệu có tiêu đề "Building an Information Technology Security Awareness and Training Program" định nghĩa ngắn gọn lý do tại sao giáo dục và đào tạo bảo mật lại quan trọng đối với người dùng. Tài liệu này định nghĩa cách cải thiện hoạt động bảo mật của một tổ chức. Tài liệu nào đang được mô tả? => NIST SP 800-50 
24. Điểm số mà CVSS cung cấp được giải thích như thế nào? => Scores are rated from 0 to 10, with 10 being the most severe
25. Hệ thống cứng hóa thuộc nhóm kiểm soát nào? => Technical 

# Example 10

3. Hai mục nào có thể được bao gồm trong thư viện? (Chọn hai.) => Các thủ tục con, Mẫu tin nhắn
9. Định nghĩa của thư viện trong phần mềm ứng dụng là gì? => Là bộ sưu tập các tài nguyên có thể được tái sử dụng bởi các chương trình.
10. Công cụ truy vấn cơ sở dữ liệu tên miền nào đã bị hạn chế bởi Quy định Bảo vệ Dữ liệu Chung (GDPR) của Liên minh Châu Âu để bảo vệ quyền riêng tư? => Whois
11. Hai công cụ nào có thể được sử dụng để thực hiện thu thập thông tin chủ động? (Chọn hai.) => Zenmap, Enum4linux
12. Hai công cụ nào có thể được sử dụng để thực hiện các cuộc tấn công vào thông tin xác thực? (Chọn hai.) => Mimikatz, Patator
13. Hệ điều hành Linux nào đi kèm với hơn 1900 công cụ kiểm thử xâm nhập bảo mật? => BlackArch Linux
14. Công cụ nào được thiết kế để tìm siêu dữ liệu và thông tin ẩn trong các tài liệu? => FOCA
15. Thành phần nào của ngôn ngữ lập trình là một khối mã có thể tái sử dụng nhiều lần để thực hiện một nhiệm vụ cụ thể? => Function
16. Công cụ nào tổ chức các thực thể truy vấn trong Entity Palette và gọi các tùy chọn tìm kiếm là “biến đổi”? => Maltego
17. Thành phần nào của ngôn ngữ lập trình là một mẫu mã bao gồm các biến và hàm ban đầu để tạo ra một đối tượng? => Class
18. Công cụ thu thập thông tin thụ động nào có thể được sử dụng để tìm thông tin về các thiết bị và mạng trên Internet? => Censys
19. Công cụ dòng lệnh nào cho phép thực thi lệnh tương tác hoặc không tương tác? => Bash
20. Bản phân phối Linux kiểm thử xâm nhập phổ biến nào dựa trên Debian GNU/Linux và phát triển từ WHoppiX, WHAX, và BackTrack? => Kali Linux
21. Công cụ quét lỗ hổng nào cung cấp dịch vụ đám mây thực hiện giám sát liên tục, quản lý lỗ hổng và kiểm tra tuân thủ? => Qualys
22. Công cụ nào là một công cụ hậu khai thác dựa trên PowerShell có thể duy trì sự kiên cố trên hệ thống bị xâm nhập và chạy các tác nhân PowerShell mà không cần powershell.exe? => Empire
23. Công cụ nào có thể được sử dụng với Metasploit để duy trì tính ẩn danh và tránh bị phát hiện bởi các kiểm soát bảo mật được triển khai bởi tổ chức? => Veil
24. Phương pháp mã hóa nào có thể được sử dụng để xâm nhập dữ liệu bí mật trong payload của các gói DNS? => Base64
25. Công cụ nào trong phân phối Linux là công cụ thu thập bằng chứng pháp lý? => CAINE


#############################################################################
############################# Course Final Exam #############################
#############################################################################

1. Hai thực hành tốt nhất được sử dụng để bảo mật API là gì? (Chọn hai)
•	Sử dụng các thư viện tiêu chuẩn và uy tín để tạo API
•	Làm tài liệu API nội bộ bắt buộc
•	Giải thích: Các thực hành bảo mật API tốt bao gồm việc sử dụng thư viện đáng tin cậy và chuẩn mực để tạo API, đồng thời làm tài liệu API nội bộ bắt buộc để đảm bảo các nhà phát triển hiểu và tuân thủ các chính sách bảo mật.
2. Loại tác nhân đe dọa nào sử dụng các cuộc tấn công tội phạm mạng để thúc đẩy những gì họ tin tưởng?
•	Hacktivists
•	Giải thích: Hacktivists là những tác nhân đe dọa không bị thúc đẩy bởi tiền bạc, mà là để thúc đẩy quan điểm của họ hoặc làm nổi bật các vấn đề mà họ tin tưởng thông qua các cuộc tấn công mạng.
3. Một công ty đã thực hiện kiểm thử xâm nhập cách đây 6 tháng. Tuy nhiên, họ đã mua các tường lửa và máy chủ mới để củng cố mạng và tăng cường năng lực. Tại sao một quản trị viên yêu cầu thực hiện lại kiểm thử xâm nhập?
•	Bề mặt tấn công đã thay đổi với các thiết bị mới được thêm vào
•	Giải thích: Khi triển khai các thiết bị mới như tường lửa và máy chủ, bề mặt tấn công của hệ thống có thể thay đổi, do đó cần kiểm tra lại khả năng bảo mật của hệ thống thông qua một kiểm thử xâm nhập mới.
4. Một quản trị viên mạng thực hiện kiểm thử xâm nhập cho một công ty bán linh kiện máy tính qua cửa hàng trực tuyến. Bước đầu tiên là tìm hiểu ai sở hữu tên miền mà công ty đang sử dụng. Công cụ kiểm thử xâm nhập nào có thể được sử dụng để làm điều này?
•	WHOIS
•	Giải thích: Lệnh whois có thể thu thập thông tin về ai sở hữu một tên miền từ các hồ sơ công khai.
5. Một người kiểm thử xâm nhập muốn nhanh chóng phát hiện tất cả các máy chủ hoạt động trên mạng 192.168.0.0/24. Lệnh nào có thể thực hiện việc quét ping bằng công cụ nmap?
•	nmap -sn 192.168.0.0/24
•	Giải thích: Lệnh nmap -sn 192.168.0.0/24 dùng để quét tất cả các máy chủ hoạt động trên mạng 192.168.0.0/24, đây là một lệnh quét cơ bản để phát hiện các máy chủ trong một dải mạng.
6. Một người kiểm thử xâm nhập chạy lệnh nmap -sF -p 80 192.168.1.1 trên một máy chủ Windows và nhận được phản hồi từ gói tin RST. Kết luận gì có thể rút ra về trạng thái cổng 80?
•	Cổng 80 đóng
•	Giải thích: Một phản hồi RST từ một máy chủ Windows sẽ chỉ ra rằng cổng 80 đóng, vì Windows sẽ luôn phản hồi với một gói RST bất kể trạng thái của cổng.
7. Công cụ phổ biến nào được người kiểm thử xâm nhập sử dụng để tạo các gói tin?
•	scapy
•	Giải thích: Scapy là một công cụ mạnh mẽ dựa trên Python, cho phép tạo và phân tích các gói tin mạng. Nó yêu cầu quyền root để có thể chỉnh sửa các gói tin.
8. Tại sao người kiểm thử nên sử dụng kỹ thuật giới hạn truy vấn khi thực hiện kiểm thử xâm nhập được ủy quyền trên mạng trực tiếp?
•	Để giảm số lượng các luồng tấn công gửi đến mục tiêu cùng một lúc
•	Giải thích: Kỹ thuật giới hạn truy vấn (query throttling) giúp giảm tải cho hệ thống mạng, bằng cách giảm số lượng các luồng tấn công đang được gửi đến mục tiêu một cách đồng thời.
9. Tại sao một tổ chức thuê một đội đỏ (red team)?
•	Để đóng vai trò của một tác nhân đe dọa bằng cách phơi bày các lỗ hổng liên quan đến công nghệ
•	Giải thích: Một đội đỏ là nhóm các chuyên gia bảo mật và người kiểm thử xâm nhập được thuê để mô phỏng một tác nhân đe dọa thực sự và tìm ra các lỗ hổng liên quan đến công nghệ, con người và bảo mật vật lý.
10. Khớp thuật ngữ trong ngành chăm sóc sức khỏe với mô tả tương ứng.
•	Healthcare provider: Người hoặc tổ chức cung cấp dịch vụ chăm sóc sức khỏe.
•	Health plan: Chương trình của chính phủ thanh toán chi phí chăm sóc sức khỏe.
•	Business associates: Người hoặc tổ chức thực hiện một số chức năng liên quan đến việc sử dụng PHI thay mặt cho, hoặc cung cấp dịch vụ cho, một thực thể có bảo hiểm.
•	Healthcare clearinghouse: Tổ chức xử lý thông tin y tế không chuẩn mà nhận được từ các tổ chức khác thành định dạng chuẩn.
11. Hai yếu tố nào thường có mặt ở mặt trước của thẻ tín dụng? (Chọn hai)
•	Chíp vi mạch nhúng
•	Số tài khoản chính (PAN)
•	Giải thích: Các yếu tố thường có trên mặt trước của thẻ tín dụng là chíp vi mạch nhúng và số tài khoản chính (PAN). Các yếu tố khác như mã bảo mật thẻ thường nằm ở mặt sau.
12. Công cụ nào có thể được sử dụng để ghi lại dòng thời gian kiểm thử trong tài liệu quy tắc tham gia?
•	Biểu đồ Gantt và cấu trúc phân rã công việc
•	Giải thích: Biểu đồ Gantt và cấu trúc phân rã công việc có thể được sử dụng để ghi lại dòng thời gian kiểm thử trong tài liệu quy tắc tham gia. Các công cụ như Burp Suite và OWASP ZAP chủ yếu được sử dụng để chặn giao tiếp giữa trình duyệt và máy chủ web.
13. Một công ty bảo mật đã được thuê để thực hiện các bài kiểm tra xâm nhập. Các bài kiểm tra này yêu cầu một phương thức an toàn để chuyển dữ liệu qua mạng. Hai giao thức nào có thể được sử dụng để thực hiện nhiệm vụ này? (Chọn hai)
•	SFTP
•	SCP
•	Giải thích: SFTP (Secure File Transfer Protocol) và SCP (Secure Copy Protocol) đều là các giao thức an toàn để chuyển tệp qua mạng.
14. Khớp phương pháp kiểm tra xâm nhập và tiêu chuẩn với mô tả tương ứng.
•	OWASP WSTG: Đây là một tập hợp các giai đoạn kiểm tra bảo mật ứng dụng web và đào sâu vào các phương pháp kiểm tra được sử dụng.
•	OSSTMM: Đây là một phương pháp kiểm tra bảo mật được duy trì bởi Viện Các Phương Pháp Mở (ISECOM), sử dụng tài liệu xác định các bài kiểm tra bảo mật có thể lặp lại và nhất quán.
•	MITRE ATT&CK: Đây là một tài nguyên học hỏi về chiến thuật, kỹ thuật và thủ tục (TTP) của kẻ tấn công, giúp người kiểm tra xâm nhập hiểu rõ hơn về các kỹ thuật và cách thức của các tác nhân đe dọa.
•	NIST: Đây là tài liệu cung cấp hướng dẫn cho các tổ chức về việc lên kế hoạch và thực hiện kiểm tra bảo mật thông tin.
15. Ba thực hành phổ biến được áp dụng khi thiết lập môi trường phòng thí nghiệm kiểm tra xâm nhập là gì? (Chọn ba)
•	Tạo môi trường kiểm tra sử dụng máy ảo và công tắc ảo
•	Đảm bảo rằng khi có sự cố, có thể xác định cách thức và lý do sự cố xảy ra
•	Sử dụng môi trường đóng cho tất cả các mục đích kiểm tra
•	Giải thích: Một môi trường kiểm tra xâm nhập điển hình nên có các yếu tố như môi trường máy ảo để dễ dàng triển khai và khôi phục thiết bị thử nghiệm, và môi trường đóng để kiểm soát và giám sát các thử nghiệm mà không ảnh hưởng đến mạng bên ngoài.
16. Một tổ chức muốn kiểm tra khả năng dễ bị tấn công của một nhân viên có quyền truy cập vào mạng. Loại bài kiểm tra xâm nhập nào nên được sử dụng để kiểm tra lỗ hổng này?
•	Kiểm thử xâm nhập loại gray-box
•	Giải thích: Kiểm thử xâm nhập loại gray-box là khi kiểm thử được thực hiện từ trong mạng nội bộ. Nhân viên thường có quyền truy cập ban đầu, và mục đích là kiểm tra khả năng tấn công từ bên trong.
17. Một người kiểm tra xâm nhập đang chuẩn bị chạy khai thác EternalBlue sử dụng Metasploit chống lại một mục tiêu có địa chỉ IP 10.0.0.1/8 từ máy chủ nguồn với địa chỉ IP 10.0.0.111/8. Hai lệnh nào phải được nhập trước khi lệnh khai thác có thể được thực thi? (Chọn hai)
•	set RHOST 10.0.0.1
•	set LHOST 10.0.0.111
•	Giải thích: Lệnh set RHOST xác định địa chỉ IP của mục tiêu, còn set LHOST xác định địa chỉ IP của máy chủ nguồn.
18. Một người kiểm tra xâm nhập chạy lệnh nmap –script smtp-open-relay.nse 10.0.0.1 trên một máy Kali Linux. Mục đích của việc chạy script này là gì?
•	Kiểm tra cấu hình relay mở trên máy chủ mục tiêu
•	Giải thích: Script smtp-open-relay.nse kiểm tra xem máy chủ SMTP có cho phép gửi email từ bất kỳ người dùng nào hay không (relay mở).
19. Một người kiểm tra xâm nhập đang chạy khai thác trên FTP để kiểm tra đăng nhập ẩn danh. Mục tiêu của khai thác này là gì?
•	Kiểm tra xem hệ thống mục tiêu có cho phép đăng nhập FTP ẩn danh hay không
•	Giải thích: Đăng nhập FTP ẩn danh cho phép người dùng không cần xác thực để truy cập hệ thống FTP. Mục tiêu của bài kiểm tra là xác định xem tính năng này có bị mở hay không.
20. Một người kiểm tra xâm nhập triển khai một điểm truy cập giả trong cơ sở hạ tầng không dây mục tiêu. Bước đầu tiên để buộc các khách hàng không dây kết nối với điểm truy cập giả là gì?
•	Gửi các khung de-authentication đến các khách hàng
•	Giải thích: Tấn công de-authentication sẽ khiến các khách hàng không dây ngắt kết nối với điểm truy cập hợp lệ và kết nối lại với điểm truy cập giả.
21. Một sinh viên bảo mật đang học về Social-Engineer Toolkit (SET), và sinh viên này phát hiện rằng công cụ này có thể được sử dụng để triển khai nhiều cuộc tấn công kỹ thuật xã hội. Hai cuộc tấn công kỹ thuật xã hội nào có thể được triển khai bằng SET?
•	Tạo tải trọng và listener
•	Tạo phương tiện truyền nhiễm
•	Giải thích: SET có thể được sử dụng để tạo các tải trọng độc hại và listener, đồng thời cũng có thể tạo các phương tiện truyền nhiễm (như USB lây nhiễm).
22. Một tác nhân đe dọa giả mạo số điện thoại của giám đốc nhân sự và gọi đến bộ phận hỗ trợ kỹ thuật với vấn đề đăng nhập. Tác nhân đe dọa này yêu cầu bộ phận hỗ trợ thay đổi mật khẩu. Phương pháp ảnh hưởng nào mà tội phạm mạng này đang sử dụng?
•	Quyền lực
•	Giải thích: Phương pháp ảnh hưởng này sử dụng quyền lực, nơi một người có chức vụ cao (như giám đốc nhân sự) yêu cầu hành động, và người khác tuân theo yêu cầu đó vì vị trí quyền lực của người đó.
23. Câu nào mô tả chính xác một loại cuộc tấn công kỹ thuật xã hội vật lý?
•	Dumpster phishing là một tác nhân đe dọa lục lọi thông tin cá nhân của nạn nhân trong thùng rác và các thùng tái chế.
•	Giải thích: Dumpster diving (lục lọi thùng rác) là khi một tác nhân đe dọa tìm kiếm thông tin nhạy cảm trong các thùng rác hoặc thùng tái chế của nạn nhân.
24. Đặc điểm của một cuộc tấn công pharming là gì?
•	Một tác nhân đe dọa chuyển hướng nạn nhân từ một trang web hợp lệ đến một trang web giả mạo trông giống trang web hợp lệ
•	Giải thích: Pharming là một cuộc tấn công mạo danh, nơi tác nhân đe dọa chuyển hướng nạn nhân từ một trang web hợp lệ đến một trang web giả mạo, có thể trông giống như trang web hợp lệ để đánh cắp thông tin nhạy cảm.
25. Loại cuộc tấn công kỹ thuật xã hội nào có thể được ngăn chặn bằng cách phát triển các chính sách như cập nhật ứng dụng chống phần mềm độc hại thường xuyên và sử dụng trình duyệt ảo bảo mật với ít kết nối đến hệ thống và mạng còn lại?
•	Tấn công watering hole
•	Giải thích: Tấn công watering hole xảy ra khi một tác nhân đe dọa xác định các trang web mà nạn nhân truy cập và tìm kiếm các lỗ hổng trên các trang web đó. Chính sách bảo mật như cập nhật phần mềm chống phần mềm độc hại và sử dụng trình duyệt ảo có thể giúp ngăn chặn loại tấn công này.
26. Một kẻ tấn công nhập chuỗi ‘John’ hoặc ‘1=1’ vào một biểu mẫu web kết nối với máy chủ SQL backend, khiến máy chủ hiển thị tất cả các bản ghi trong bảng cơ sở dữ liệu. Loại tấn công SQL injection nào đã được sử dụng trong kịch bản này?
•	SQL injection kiểu Boolean
•	Giải thích: Chuỗi ‘1=1’ luôn đúng, do đó chuỗi tìm kiếm này đóng vai trò như một giá trị Boolean TRUE, khiến hệ thống cơ sở dữ liệu hiển thị tất cả các bản ghi.
27. Hai ví dụ về truy vấn không thay đổi (immutable queries) nên được sử dụng như các biện pháp giảm thiểu lỗ hổng SQL injection là gì? (Chọn hai)
•	Truy vấn tĩnh (Static queries)
•	Truy vấn có tham số (Parameterized queries)
•	Giải thích: Các truy vấn không thay đổi, bao gồm truy vấn tĩnh và truy vấn có tham số, giúp giảm thiểu lỗ hổng SQL injection.
28. Một kẻ tấn công nhập chuỗi 192.168.78.6;cat /etc/httpd/httpd.conf vào một ứng dụng web lưu trữ trên máy chủ Linux. Loại tấn công nào đã xảy ra?
•	Tấn công tiêm lệnh (Command injection)
•	Giải thích: Tiêm lệnh là một cuộc tấn công trong đó kẻ tấn công cố gắng thực thi các lệnh hệ điều hành mà lẽ ra chúng không được phép thực hiện trên hệ thống.
29. Hai phương thức xác thực đám mây được cấu hình sai có thể lợi dụng tài sản đám mây là gì? (Chọn hai)
•	Xác thực liên kết (Federated authentication)
•	Quản lý danh tính và truy cập (IAM)
•	Giải thích: Các tấn công có thể lợi dụng các tài sản đám mây cấu hình sai bao gồm các lỗi cấu hình trong xác thực liên kết và các triển khai IAM.
30. Khớp tấn công đám mây với mô tả tương ứng.
•	Credential Harvesting: Quá trình thu thập và đánh cắp tên người dùng, mật khẩu, mã thông báo, mã PIN và các loại chứng chỉ khác thông qua các lỗ hổng cơ sở hạ tầng.
•	Privilege Escalation: Lợi dụng một lỗi hoặc lỗi thiết kế trong phần mềm hoặc ứng dụng firmware để truy cập các tài nguyên vốn được bảo vệ khỏi một ứng dụng hoặc người dùng.
•	Account Takeover: Khi một tác nhân đe dọa chiếm đoạt quyền truy cập vào một tài khoản người dùng hoặc ứng dụng và sử dụng tài khoản đó để truy cập thêm nhiều tài khoản và thông tin.
31. Mục đích của việc sử dụng lệnh smtp-user-enum -M VRFY -u snp -t 10.0.0.1 trong Kali Linux là gì?
•	Kiểm tra xem người dùng snp có tồn tại trên máy chủ SMTP 10.0.0.1 hay không
•	Giải thích: Lệnh smtp-user-enum với tùy chọn -M VRFY được sử dụng để xác minh sự tồn tại của một người dùng trên máy chủ SMTP.
32. Khớp công cụ kiểm tra bảo mật thiết bị di động với mô tả.
•	Burp Suite: Công cụ này có thể kiểm tra các ứng dụng di động và xác định cách chúng giao tiếp với các dịch vụ web và API.
•	Drozer: Nền tảng kiểm tra Android này cung cấp quyền truy cập vào nhiều khai thác có thể được sử dụng để tấn công các nền tảng Android.
•	Needle: Framework mã nguồn mở này được sử dụng để kiểm tra bảo mật của các ứng dụng iOS.
•	ApkX: Công cụ này cho phép bạn giải nén các tệp gói ứng dụng Android (APK).
33. Khớp tấn công thiết bị di động với mô tả.
•	Sandbox analysis: Phương pháp này có thể giúp một tác nhân đe dọa vượt qua các cơ chế kiểm soát truy cập được triển khai bởi Android, Apple iOS và các nhà phát triển ứng dụng di động.
•	Spamming: Tấn công này sử dụng các liên kết để chuyển hướng người dùng đến các trang web độc hại nhằm đánh cắp thông tin nhạy cảm hoặc cài đặt phần mềm độc hại.
•	Reverse engineering: Quá trình phân tích ứng dụng di động để trích xuất thông tin về mã nguồn nhằm hiểu rõ hơn về cấu trúc cơ bản của ứng dụng và có thể thao túng thiết bị di động.
34. Hai tuyên bố đúng về Bluetooth Low Energy (BLE) là gì? (Chọn hai)
•	Kẻ tấn công có thể nghe quảng cáo BLE và tận dụng các cấu hình sai.
•	BLE quảng cáo có thể bị nghe lén bằng các ăng-ten và thiết bị chuyên dụng.
•	Giải thích: Nhiều thiết bị hỗ trợ BLE không thực hiện mã hóa ở tầng BLE. Kẻ tấn công có thể nghe các quảng cáo BLE và lợi dụng các cấu hình không chính xác.
35. Khớp thực hành mã không an toàn với mô tả.
•	Hard-coded credentials: Một lỗi nghiêm trọng mà kẻ tấn công có thể lợi dụng để hoàn toàn chiếm đoạt một ứng dụng hoặc hệ thống.
•	Comments in source code: Các nhà phát triển có thể vô tình đưa thông tin quá chi tiết vào mã nguồn, cung cấp thông tin có thể bị lợi dụng bởi kẻ tấn công.
•	Lack of error handling and overly verbose error handling: Một loại yếu điểm và lỗi bảo mật có thể cung cấp thông tin giúp kẻ tấn công thực hiện các cuộc tấn công bổ sung.
•	Unprotected APIs: Nhiều API thiếu các kiểm soát thích hợp và khó theo dõi, làm cho việc kiểm tra bảo mật trở nên khó khăn.
36. Công cụ C2 nào có thể được sử dụng để tạo nhiều reverse shell?
•	Socat
•	Giải thích: Socat là một công cụ C2 có thể được sử dụng để tạo nhiều reverse shell.
37. Khớp mô-đun PowerSploit với mô tả tương ứng.
•	Invoke-Portscan: Thực hiện quét cổng TCP đơn giản sử dụng các socket thông thường.
•	PowerUp: Đóng vai trò là kho tập hợp các kiểm tra leo thang đặc quyền, cùng với một số vector vũ khí hóa.
•	PowerView: Thực hiện việc xác minh và khai thác mạng và miền Windows.
•	Get-VaultCredential: Hiển thị các đối tượng thông tin xác thực trong Windows Vault, bao gồm mật khẩu web dạng văn bản thuần.
38. Hai công cụ có thể tạo kết nối từ xa với hệ thống bị xâm nhập là gì? (Chọn hai)
•	Metasploit
•	Sysinternals
•	Giải thích: Metasploit có thể được sử dụng để tạo kết nối RDP với một hệ thống bị xâm nhập, trong khi Sysinternals là một bộ công cụ cho phép quản trị viên kiểm soát máy tính Windows từ xa.
39. Hai mô-đun/skript PowerSploit là gì? (Chọn hai)
•	Get-Keystrokes
•	Get-SecurityPackages
•	Giải thích: PowerSploit là bộ công cụ PowerShell cho post-exploitation. Các mô-đun như Get-Keystrokes (ghi lại các phím được nhấn) và Get-SecurityPackages (liệt kê tất cả các gói bảo mật đã tải) rất hữu ích trong việc thu thập thông tin từ hệ thống bị xâm nhập.
40. Tại sao quan trọng khi sử dụng Hệ thống Đánh giá Mức độ Rủi ro Lỗ hổng (CVSS) để tham chiếu các mức độ xếp hạng lỗ hổng khi chuẩn bị báo cáo kiểm tra xâm nhập cuối cùng?
•	Nó đã được nhiều công cụ, nhà cung cấp và tổ chức áp dụng.
•	Giải thích: CVSS là một tiêu chuẩn quốc tế giúp xếp hạng mức độ nghiêm trọng của các lỗ hổng, giúp tăng giá trị của báo cáo kiểm tra xâm nhập cuối cùng.
41. Một công ty thuê một chuyên gia để thực hiện kiểm tra xâm nhập. Người kiểm tra đã xác định và xác minh rằng một ứng dụng web dễ bị tấn công SQL injection và cross-site scripting. Biện pháp kiểm soát kỹ thuật nào nên được người kiểm tra khuyến nghị cho công ty?
•	Làm sạch đầu vào người dùng (user input sanitization)
•	Giải thích: Các phương pháp như kiểm tra đầu vào và làm sạch dữ liệu nhập vào của người dùng giúp ngăn chặn các lỗ hổng như SQL injection và cross-site scripting.
42. Phòng ban IT của một công ty đã phát triển một chính sách truy cập cho trung tâm dữ liệu. Chính sách quy định rằng trung tâm dữ liệu sẽ bị khóa từ 5:30 pm đến 7:45 am hàng ngày, ngoại trừ khi có truy cập khẩn cấp được phê duyệt bởi quản lý IT. Biện pháp kiểm soát hoạt động được thực hiện là gì?
•	Hạn chế theo thời gian trong ngày (time-of-day restrictions)
•	Giải thích: Chính sách hạn chế truy cập theo thời gian trong ngày giúp kiểm soát người dùng có thể truy cập vào trung tâm dữ liệu vào những thời điểm nhất định.
43. Một cuộc kiểm tra bảo mật của công ty khuyến nghị công ty triển khai xác thực đa yếu tố cho truy cập trung tâm dữ liệu. Giải pháp nào sẽ đạt được mục tiêu này?
•	Kiểm soát sinh trắc học (biometric controls)
•	Giải thích: Kiểm soát sinh trắc học, chẳng hạn như quét vân tay và nhận diện khuôn mặt, kết hợp với mật khẩu mạnh sẽ cung cấp xác thực đa yếu tố hiệu quả.
44. Ba ví dụ về các mục mà một người kiểm tra xâm nhập phải làm sạch khỏi hệ thống như một phần của quy trình dọn dẹp sau khi kết thúc bài kiểm tra là gì? (Chọn ba)
•	Tài khoản do người kiểm tra tạo ra
•	Shells
•	Công cụ
•	Giải thích: Sau khi hoàn thành kiểm tra, việc dọn dẹp các tài khoản do người kiểm tra tạo ra, loại bỏ các shell đã mở và xóa công cụ đã sử dụng là rất quan trọng để đảm bảo không còn dấu vết nào trong hệ thống.
45. Ba ví dụ về các mục mà một người kiểm tra xâm nhập phải làm sạch khỏi hệ thống như một phần của quy trình dọn dẹp sau khi kết thúc bài kiểm tra là gì? (Chọn ba)
•	Tài khoản do người kiểm tra tạo ra
•	Shells
•	Công cụ
Giải thích: Sau khi hoàn thành các giai đoạn kiểm tra của một bài kiểm tra xâm nhập, việc dọn dẹp sau kiểm tra là rất quan trọng. Các mục cần làm sạch bao gồm:
•	Tài khoản do người kiểm tra tạo ra: Loại bỏ bất kỳ tài khoản người dùng nào mà bạn đã tạo để duy trì quyền truy cập lâu dài hoặc cho các hoạt động hậu khai thác.
•	Shells: Loại bỏ bất kỳ shell nào đã được tạo ra trên các hệ thống bị khai thác.
•	Công cụ: Loại bỏ bất kỳ công cụ nào đã được cài đặt hoặc chạy trên các hệ thống kiểm tra.
46. Khớp cấu trúc dữ liệu Python với mô tả trong hình minh họa.
•	Dictionary
Giải thích: Một dictionary là một bộ sưu tập các giá trị dữ liệu được sắp xếp theo cặp khóa/giá trị.
47. Mệnh đề nào mô tả đúng khái niệm của Bash shell trong các hệ điều hành?
•	Bash shell là một shell lệnh và trình thông dịch ngôn ngữ cho hệ điều hành.
Giải thích: Bash shell là một shell lệnh và trình thông dịch ngôn ngữ có sẵn cho các hệ điều hành như Linux, macOS và Windows. Nó cho phép thực thi lệnh theo chế độ tương tác hoặc không tương tác.
48. Ba công cụ có thể được sử dụng để thực hiện thu thập thông tin thụ động là gì? (Chọn ba)
•	Dig
•	Nslookup
•	Host
Giải thích: Nslookup, Host và Dig là các công cụ dựa trên DNS có thể được sử dụng để thực hiện thu thập thông tin thụ động. Nmap, Zenmap và Enum4linux là các công cụ thu thập thông tin chủ động.
49. Một kẻ tấn công sử dụng John the Ripper để giải mã một tệp mật khẩu. Kẻ tấn công đã nhập lệnh ~$ john –list=formats trong Kali Linux. Kẻ tấn công đang cố gắng tìm kiếm thông tin gì?
•	Các định dạng cipher text được hỗ trợ bởi phiên bản hiện tại
Giải thích: John the Ripper là một công cụ phổ biến để giải mã mật khẩu ngoại tuyến. John the Ripper hỗ trợ nhiều chế độ giải mã và hiểu nhiều định dạng cipher text khác nhau. Để liệt kê các định dạng được hỗ trợ, kẻ tấn công có thể sử dụng lệnh john --list=formats.
50. Hai framework khai thác phổ biến là gì? (Chọn hai) Metasploit, BeEF
