# Các loại thiết bị mạng sẽ sử dụng khi bạn xây dựng mạng

Mạng không thể tồn tại trừ khi mỗi thiết bị có phương tiện giao tiếp với thiết bị khác. Thực tế này áp dụng cho dù đó là mạng của tổ chức bạn hay các mạng rộng lớn hơn, như web. Tất cả các mạng đều được xây dựng trên các nguyên tắc giống nhau.

Trong phần này, bạn sẽ tìm hiểu về thuật ngữ tiêu chuẩn mạng và khám phá phần cứng tạo thành xương sống của bất kỳ mạng nào.
Tiêu chuẩn mạng

Trong khi các giao thức mạng cung cấp một phương pháp thống nhất để giao tiếp, các tiêu chuẩn mạng sẽ chi phối phần cứng và phần mềm sử dụng chúng.

Ngày nay, có hàng trăm nghìn nhà cung cấp phần cứng, nhưng tất cả công nghệ của họ đều tích hợp liền mạch với máy tính hoặc mạng của bạn mà không tốn nhiều công sức. Các tiêu chuẩn mạng cung cấp một khuôn khổ cho phép khả năng tương tác giữa các thiết bị.

Các tiêu chuẩn mạng cải thiện khả năng tương tác của các thiết bị hỗ trợ mạng khác nhau và cung cấp khả năng tương thích ngược giữa các phiên bản sản phẩm và các nhà cung cấp khác nhau. Các cơ quan chính thức xuất bản các tiêu chuẩn được quy định là Liên minh Viễn thông Quốc tế (ITU), Viện Tiêu chuẩn Quốc gia Hoa Kỳ (ANSI) và Viện Kỹ sư Điện và Điện tử (IEEE).

Sẽ không thể xây dựng mạng và kết nối các thiết bị hỗ trợ mạng một cách đáng tin cậy nếu không có các tiêu chuẩn mạng.
Họ tiêu chuẩn 802

Đặc điểm kỹ thuật 802 bao gồm tất cả các tiêu chuẩn mạng vật lý cho cả Ethernet và không dây. Bảng sau đây cho thấy một số tiêu chuẩn được sử dụng rộng rãi hơn.
802 	Tổng quan 	Khái niệm cơ bản về các khái niệm mạng vật lý và logic
802.1 	Bắc cầu 	Kết nối LAN / MAN và quản lý các lớp con thấp hơn của OSI Lớp 2
802.2 	Liên kết logic 	Thường được gọi là thông số kỹ thuật điều khiển liên kết logic (LLC)
802.3 	Ethernet 	Cung cấp mạng không đồng bộ bằng cách sử dụng cảm biến sóng mang, nhiều truy cập với phát hiện xung đột (CSMA / CD) qua cáp đồng trục, cáp đồng xoắn đôi và phương tiện truyền thông sợi
802.5 	Vòng mã thông báo 	Tiêu chuẩn truyền mã thông báo cho cáp đồng được bảo vệ và cáp xoắn đôi
802.11 	Wifi 	Đặc điểm kỹ thuật kiểm soát truy cập phương tiện mạng cục bộ (WLAN) không dây (MAC) và lớp vật lý (PHY)
802.11a 	Wifi 	Chỉ định PHY hoạt động ở 5 GHz
802.11b 	Wifi 	Cải thiện 802.11, thêm các chế độ tốc độ dữ liệu cao hơn
802.11d 	Wifi 	Cải tiến 802.11a / b, cho phép chuyển vùng toàn cầu
802.11e 	Wifi 	Cải tiến 802.11, bổ sung các tính năng Chất lượng Dịch vụ (QoS)
802.11g 	Wifi 	Mở rộng tốc độ dữ liệu tối đa của mạng WLAN
802.11 giờ 	Wifi 	Nâng cao 802.11a, hiện giải quyết các vấn đề về nhiễu
802.11i 	Wifi 	Tăng cường 802.11, bổ sung bảo mật cho các ứng dụng WLAN
802.11j 	Wifi 	Tăng cường 802.11a cho các phần mở rộng quy định của Nhật Bản
802.11n 	Wifi 	Tiêu chuẩn tốc độ cao hơn
802.12 	Ưu tiên nhu cầu 	Tốc độ dữ liệu Ethernet tăng lên 100 Mbps
802.15 	Mạng khu vực cá nhân không dây 	Hỗ trợ mạng khu vực cá nhân không dây (WPAN)
802.15.1 	Bluetooth 	Công nghệ không dây tầm ngắn (10 m)
802.15.3a 	UWB 	Liên kết băng thông cực rộng (UWB) tầm ngắn, băng thông cao
802.15.4 	ZigBee 	Mạng cảm biến không dây tầm ngắn
802.16 	Mạng khu vực đô thị không dây 	Bao phủ truy cập băng thông rộng di động và không dây trong các mạng khu vực đô thị không dây (WMAN)
Cơ sở hạ tầng mạng

Có một số thiết bị tuân thủ tiêu chuẩn mạng tạo nên cấu trúc mạng của bạn. Tùy thuộc vào quy mô mạng, bạn có thể sử dụng một số thiết bị này để xây dựng xương sống cho mạng của mình. Các thiết bị này là:

    Bộ lặp lại
    Trung tâm
    Cầu
    Công tắc
    Bộ định tuyến

Gần như tất cả các thiết bị này phụ thuộc vào điều khiển truy cập phương tiện hoặc địa chỉ Giao thức Internet (IP) để cung cấp dữ liệu trên mạng.
Địa chỉ kiểm soát truy cập phương tiện là gì?

Địa chỉ kiểm soát truy cập phương tiện (MAC) là số nhận dạng duy nhất được gán cho mọi thiết bị hỗ trợ mạng tại thời điểm sản xuất. Nó đôi khi được gọi là địa chỉ đã ghi, địa chỉ phần cứng Ethernet hoặc địa chỉ vật lý.

Ảnh chụp màn hình hiển thị thông tin địa chỉ của thiết bị mạng được trả về khi chạy lệnh ipconfig / all.

Địa chỉ MAC có thành phần tiêu chuẩn gồm sáu số thập lục phân được phân tách bằng dấu hai chấm hoặc dấu gạch ngang. Ba số đầu tiên của địa chỉ MAC xác định mã định danh duy nhất về mặt tổ chức (OUI) của nhà sản xuất và ba số còn lại xác định duy nhất thiết bị. Ví dụ: nếu địa chỉ MAC là AA-6A-BA-2B-68-C1thì OUI là AA-6A-BAvà 2B-68-C1là ID thiết bị.
Bộ lặp

Bộ lặp là một thiết bị hai cổng lặp lại các tín hiệu mạng. Bộ lặp được sử dụng khi các thiết bị mạng cách xa nhau. Bộ lặp không sửa đổi hoặc giải thích các gói dữ liệu trước khi gửi lại và nó không khuếch đại tín hiệu. Thay vào đó, nó tái tạo gói dữ liệu ở độ mạnh ban đầu, từng chút một.
Cầu

Cầu nối chia mạng thành các phân đoạn mạng và có thể lọc và chuyển tiếp các gói dữ liệu giữa các phân đoạn này. Các cầu nối sử dụng địa chỉ MAC của thiết bị mạng để quyết định điểm đến của gói dữ liệu. Thông thường, một cầu nối được sử dụng để cải thiện hiệu suất mạng bằng cách giảm lưu lượng mạng không cần thiết trên các phân đoạn mạng.
Hub

Một trung tâm hoạt động như một bộ lặp đa cổng trên mạng. Các trung tâm được sử dụng để kết nối nhiều hơn một thiết bị và cấu trúc bố cục của một mạng. Ví dụ: bạn có thể phân tầng các trung tâm để tạo các nhánh mạng hoặc làm điểm cuối để tạo bố cục hình sao với các thiết bị kiểu nhiều người dùng. Hub chứa nhiều cổng hoạt động như một kết nối Ethernet đầu vào / đầu ra giữa trung tâm và thiết bị mạng. Một trung tâm chỉ có thể hoạt động ở một tốc độ, đó là tốc độ của thiết bị mạng chậm nhất trên mạng. Nó không giải thích hoặc lọc các gói dữ liệu và gửi các bản sao của mỗi gói dữ liệu đến tất cả các thiết bị được đính kèm.
Các loại trung tâm

    Fast Ethernet : Trung tâm này được sử dụng cho mạng 100-Mbps và có dạng trung tâm loại I và loại II. Sự khác biệt chính giữa hai loại này là độ trễ trong quá trình truyền dữ liệu. Một trung tâm Lớp I giới thiệu độ trễ tín hiệu lên đến 140-bit lần. Một trung tâm Class II có độ trễ lên đến 96 bit lần. Độ trễ cho phép chuyển mã dữ liệu giữa các loại cơ sở khác nhau. Chỉ có hai trung tâm loại II có thể được sử dụng trong mạng dựa trên trung tâm. Các trung tâm lớp II làm tăng khả năng xung đột gói vì tốc độ cao hơn.
    Tốc độ kép : Với mạng trung tâm truyền thống, tốc độ của mạng được điều chỉnh bởi thiết bị mạng chậm nhất được gắn vào. Ví dụ: nếu bạn có thiết bị 10 Mb / giây và 100 Mb / giây được kết nối với một mạng, tốc độ của toàn mạng chỉ là 10 Mb / giây. Các trung tâm tốc độ kép giải quyết vấn đề bằng cách hoạt động như một cầu nối giữa hai thiết bị tốc độ khác nhau.

Các trung tâm được sử dụng cho các mạng đặc biệt nhỏ của một số thiết bị, nhưng chúng hiếm khi được sử dụng ở cấp doanh nghiệp.
Công tắc

Một công tắc kết hợp chức năng của một cầu nối và một trung tâm. Nó phân đoạn các mạng và có thể giải thích và lọc dữ liệu gói để gửi trực tiếp đến một thiết bị mạng được đính kèm. Bộ chuyển mạch sử dụng địa chỉ MAC của thiết bị mạng để quyết định điểm đến của gói dữ liệu. Một bộ chuyển mạch hoạt động ở chế độ song công, có nghĩa là nó có thể gửi và nhận dữ liệu đến và từ các thiết bị mạng cùng một lúc.
Đặc trưng

Các thiết bị chuyển mạch dựa trên Ethernet hiện đại cung cấp nhiều chức năng và khả năng hơn một trung tâm Ethernet.

    Bộ chuyển mạch Ethernet có thể điều chỉnh tốc độ kết nối của gói đến để phù hợp với tốc độ kết nối của mạng đích.
    Nhiều thiết bị chuyển mạch hiện hỗ trợ Cấp nguồn qua Ethernet (PoE). PoE cho phép các thiết bị mạng như điện thoại Thoại qua IP (VoIP) lấy điện từ bộ chuyển mạch mà không cần nguồn điện riêng.
    Other modules can be attached to the switch to enable functions like port mirroring, packet sniffers, and intrusion-detection systems.

Types of Ethernet switch

The two distinct types of switch are unmanaged and managed.
Unmanaged

This type of switch has no configuration capability, and is designed for small-office or home-office environments. Packet switching occurs automatically.
Managed

This type of switch offers the means to adjust the configuration, behavior, and operation of the switch. Access to the switch configuration is either through a command-line interface (CLI) that uses Telnet or Secure Shell (SSH), Remote Console, or via a web interface.

Here's a list of the more commonly available options to configure on a managed switch. Keep in mind that switch manufacturers might offer different configuration options.

    Quality of Service: Manage LAN traffic so that critical systems are given higher priority. An example is voice-data packets, which need to be delivered quickly.
    Virtual LANs: Create logical groups of devices in their own virtual LAN. Traffic in one virtual LAN doesn't cross over into another virtual LAN. This logical group of devices can improve the security and performance of the network.
    Giao thức Spanning Tree (STP) : Xây dựng khả năng phục hồi cho mạng của bạn bằng cách xác định các tuyến mạng thay thế trong trường hợp cáp hoặc thiết bị bị lỗi.
    Phản chiếu cổng : Sử dụng với máy phân tích mạng để chẩn đoán các vấn đề và sự cố mạng. Trong quá trình thiết lập, công tắc xuất một bản sao của lưu lượng mạng sang một cổng duy nhất.
    Giới hạn tốc độ băng thông : Cho phép kiểm soát tốt băng thông được sử dụng bởi các cổng cụ thể, chẳng hạn như băng thông cao cho các cổng xử lý cơ sở dữ liệu hoặc VoIP và băng thông thấp hơn cho email.
    Lọc địa chỉ MAC : Cung cấp khả năng kiểm soát thiết bị mạng nào có thể được sử dụng hoặc có quyền truy cập thông qua bộ chuyển mạch.
    Máy khách SNMP : Thiết lập và định cấu hình SNMP bằng các công cụ giám sát mạng của bạn.

Có hai loại phụ của thiết bị chuyển mạch được quản lý:

    Thông minh : Công tắc thông minh là điểm nằm giữa công tắc không được quản lý và công tắc được quản lý. Họ có xu hướng chỉ cung cấp giao diện dựa trên web để quản lý cấu hình. Các tùy chọn khả dụng là mạng LAN ảo, phản chiếu cổng và giới hạn tốc độ băng thông.
    Doanh nghiệp : Dịch vụ chuyển mạch được quản lý hoàn toàn đã mô tả trước đây.

Bộ định tuyến

Bộ định tuyến liên kết các mạng với các địa chỉ có phạm vi khác nhau với nhau. Họ có thể giải thích và lọc các gói dữ liệu, sau đó chuyển tiếp chúng đến đúng mạng. Bộ định tuyến sử dụng thông tin địa chỉ IP của thiết bị mạng để định tuyến gói dữ liệu đến đích của nó. Hầu hết các bộ định tuyến hiện có thể phát hiện các vấn đề với lưu lượng dữ liệu truyền đến bất kỳ mạng nào được đính kèm và định tuyến hoặc định tuyến lại xung quanh vấn đề. Một bộ định tuyến còn được gọi là một cổng vào. Khi bạn định cấu hình thiết bị mạng, bạn thường sẽ định cấu hình chúng bằng địa chỉ IP cổng mặc định.
Sự liên kết

Các bộ định tuyến trong một mạng liên kết duy trì một bảng định tuyến liệt kê tuyến đường ưu tiên giữa mỗi mạng. Bộ định tuyến đóng vai trò là người bắt đầu phân quyền cho tất cả các thiết bị mạng trên mạng của nó. Thông tin định tuyến được chia sẻ giữa các bộ định tuyến bằng cách sử dụng một giao thức định tuyến như Giao thức Cổng biên giới (BGP).
Các loại

The majority of routers use the BGP to share routing information. The type of information shared depends on the usage of the router and the functions they use.

There are several distinct classifications or types of routers available to service different network needs.

    Access routers: Typically used in a home or small satellite offices, these routers tend to be low-cost devices with a simple routing need.
    Distribution routers: These routers compile traffic routing data from multiple routers. Distribution routers come with more significant memory and processing power. This type of router is designed to hold vast quantities of routing information. It's often used to manage and control the quality of service across a WAN.
    Edge routers: An edge router operates at the boundary between your network and other networks; for example, your local network and the internet. They act as gateways to filter traffic and route it internally or forward it based on the packet header. An edge router often comes with access control or firewalls to improve the security. It might also handle DHCP and DNS services.
    Core routers: Sometimes called enterprise routers, these routers are designed for higher bandwidths. They're used to connect different buildings or geographic locations together. Core routers tend to have fewer features than edge routers because their primary focus is on minimizing packet loss and preventing congestion. They tend to do packet forwarding to edge routers.

Bộ phát wifi

Thiết bị mạng này cung cấp tất cả các khả năng định tuyến của một bộ định tuyến truy cập thông thường, nhưng nó cũng cung cấp các chức năng điểm truy cập không dây. Bộ định tuyến không dây hoặc điểm truy cập không dây được thiết kế để cung cấp kết nối không dây với mạng của bạn. Bất kỳ điều khoản nào để truy cập internet hoặc các mạng khác đều được xử lý bởi một bộ định tuyến biên được liên kết với mạng của bạn. Bộ định tuyến không dây cho phép bạn xây dựng một loại mạng khác được gọi là mạng cục bộ không dây.

Không nên nhầm lẫn bộ định tuyến không dây với modem không dây. Modem không dây là thứ bạn nhận được từ ISP cho gia đình hoặc văn phòng của mình và là thiết bị chuyển đổi tín hiệu từ ISP thành tín hiệu có thể sử dụng được trên mạng máy tính. Modem không dây thường được kết hợp với bộ định tuyến để cho phép bạn tạo mạng gia đình hoặc mạng văn phòng riêng.
Tùy chọn Azure

Hai tùy chọn Azure có thể giúp định tuyến và quản lý lưu lượng mạng.
Trung tâm Azure

Trung tâm Azure là một kiến trúc tham chiếu. Trung tâm thường là mạng ảo Azure hoạt động như điểm kết nối trung tâm giữa đám mây và mạng tại chỗ. Mỗi chấu cũng là một mạng ảo Azure, thường được kết nối với trung tâm thông qua mạng ngang hàng. Kết nối giữa đám mây và mạng tại chỗ có thể được thực hiện thông qua cổng VPN hoặc Azure ExpressRoute.
Azure ExpressRoute

Kết nối ExpressRoute là một mạch chuyên dụng giữa mạng tại chỗ và đám mây sử dụng băng thông cao hơn nhiều so với kết nối cổng VPN thông thường. Một mạch ExpressRoute được tổ chức bởi một đối tác kết nối và cung cấp một kết nối siêu linh hoạt. 