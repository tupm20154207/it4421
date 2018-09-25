# Software Requirement Specification

## Table of Contents

*   [Introduction](#introduction)
    *   [Purpose](#purpose)
    *   [Scope](#scope)
    *   [Glossary](#glossary)
    *   [References](#references)
    *   [Overview of Document](#overview-of-document)
*   [Overall Description](#overall-description)
    *   [System Environment](#system-environment)
    *   [Functional Requirements Definition](#functional-requirements-definition)
        *   [Survey Description](#survey-description)
        *   [Usecases](#usecases)
    *   [User Interface Specification](#user-interface-specification)
    *   [Non-Functional Requirements](#non-functional-requirements)
    *   [System Evolution](#system-evolution)
*   [Requirement Specification](#requirement-specification)
    *   [External Interface Requirements](#external-interface-requirements)
    *   [Functional Requirements](#functional-requirements)
    *   [Detailed Non-Functional Requirement](#detailed-non-functional-requirement)
*   [Index](#index)
*   [Appendix - User Interface Specifications](#appendix-user-interface-specifications)

## Introduction

(Giới thiệu)

### Purpose

(Mục đích của tài liệu)

Chỉ ra mục đích của tài liệu (mô tả đầy đủ các chức năng và ràng buộc của hệ thống) và đối tượng mà tài liệu hướng đến (người sử dụng hệ thống, các nhà phát triển hệ thống)

### Scope

(Phạm vi tài liệu)

Tổng quan về nhu cầu, ngữ cảnh và lí do cần phải triển khai hệ thống:

*   Dữ liệu mà hệ thống thu thập
*   Quá trình xử lý dữ liệu và kết quả đầu ra
*   Sự ưu việt của hệ thống đối với các phương pháp truyền thống

### Glossary

(Bảng thuật ngữ)

Bảng thuật ngữ giải thích các thuật ngữ để các nhà phát triển có được cách hiểu chung khi đọc tài liệu.

### References

(Tham chiếu)

Tham chiếu đến các tài liệu khác trong quy trình.

### Overview of Document

(Tổng quan về tài liệu)

Hướng dẫn đọc tài liệu.

"Tài liệu này gồm hai chương chính. Chương đầu ("Mô tả tổng quát") được thiết kế dành cho những thành viên trong nhà hàng trực tiếp sử dụng hệ thống. Nó liệt kê tất cả các chức năng mà hệ thống có thể thực hiện dưới các ràng buộc cụ thể. Chương thứ hai ("Chi tiết yêu cầu") mô tả các ràng buộc và chức năng của hệ thống một cách chi tiết với đầy đủ các thông tin mà các nhà phát triển cần để triển khai hệ thống. Hai chương này có khả năng tham chiếu lẫn nhau để tiện cho việc so sánh."

## Overall Description

(Mô tả tổng quát)

### System Environment

(Môi trường hệ thống)

Lập **biểu đồ ca sử dụng tổng quan** cho hệ thống và giải thích nó. Biểu đồ này có chức năng hoạch định ra giới hạn của hệ thống (các thành phần bên trong và bên ngoài của hệ thống) và trợ giúp trong việc giải thích các chức năng của hệ thống liệt kê bên dưới.

### Functional Requirements Definition

(Định nghĩa các yêu cầu chức năng)

#### Survey Description

(Mô tả ca sử dụng)

Mô tả tổng quát đối với mỗi ca sử dụng, tác nhân nào sử dụng thành phần nào và nhận về kết quả nào

#### Usecases

(Ca sử dụng #N: Tên CSD)

Với mỗi ca sử dụng, cần có các thành phần sau:

*   Biểu đồ ca sử dụng
*   Đặc tả ca sử dụng
    *   Mô tả chung:
        *   Tên ca sử dụng
        *   Nội dung tóm tắt
        *   Tác nhân
    *   Mô tả chi tiết:
        *   Điều kiện đầu vào: Điều kiện tiên quyết để ca sử dụng có thể bắt đầu
        *   Kịch bản chính: Vẽ một bảng gồm 2 cột, cột bên trái là các thao tác của tác nhân, cột bên phải là phản hồi của hệ thống
        *   Các kịch bản ngoại lệ: Bất kỳ kịch bản nào làm cho dữ liệu đầu vào không đầy đủ hoặc không chuẩn tắc dẫn đến hệ thống báo lỗi. Chỉ rõ thời điểm xảy ra kịch bản ngoại lệ tại vị trí nào của luồng kịch bản chính
        *   Các ràng buộc hoặc xung đột: Các kịch bản khiến ca sử dụng không hoạt động (nhiều người cùng ghi dữ liệu một lúc, truy cập lúc hệ thống đang offline, ...)
*   Xem thêm chi tiết yêu cầu ca sử dụng tại [tham chiếu đến ca sử dụng tương ứng trong phần chi tiết yêu cầu]

### User Interface Specification

(Giao diện người dùng)

*   Yêu cầu đối với người dùng hệ thống
*   Mô tả sơ lược về giao diện người dùng

### Non-Functional Requirements

(Các yêu cầu phi chức năng)

*   "Dưới đây là những yêu cầu phi chức năng, hay là những điều kiện và ràng buộc để các yêu cầu chức năng của hệ thống có thể được đáp ứng."
*   Xem thêm tại tài liệu "terminologies.md" đi kèm

### System Evolution

(Định hướng phát triển hệ thống)

*   Ghi lại các dự định thay đổi và nâng cấp hệ thống trong tương lai một cách đầy đủ và thiết thực

## Requirement Specification

(Chi tiết yêu cầu)

(Phần này mục đích chính là hướng tới các nhà phát triển phần mềm nhưng cũng phải đủ dễ hiểu đối với người dùng bởi vì họ có thể dùng nó để lấy thêm thông tin chi tiết về từng ca sử dụng.)

### External Interface Requirements

(Yêu cầu giao diện ngoài)

Yêu cầu về các định dạng dữ liệu của các hệ thống bên ngoài (nếu có).

Ví dụ như dữ liệu quản lý thu chi trước đó phải ở định dạng .xls hoặc .xlsx để có thể import vào hệ thống mà không xảy ra lỗi.

### Functional Requirements

(Các yêu cầu chức năng)

Với mỗi ca sử dụng, kẻ ra một bảng với các trường:

*   Tên ca sử dụng
*   Độ ưu tiên
*   Sự kiện kích hoạt
*   Điều kiện tiên quyết
*   Luồng xử lý dữ liệu: Đưa ra thứ tự xử lý, cập nhật dữ liệu được thực hiện bởi hệ thống trong ca sử dụng
*   Luồng phụ
*   Trạng thái cần đạt
*   Luồng ngoại lệ
*   Xem thêm: Tham chiếu đến ca sử dụng tương ứng trong phần mô tả tổng quan
*   Khác: Các thông tin bổ sung cho ca sử dụng

Nếu các luồng xử lý phức tạp, hãy mô tả chúng bằng một biểu đồ chuyển trạng thái (state transition diagram) hay biểu đồ hoạt động (activity diagram) thay vì giải thích bằng lời

### Detailed Non-Functional Requirement

(Chi tiết các yêu cầu phi chức năng)

*   Phần cứng
*   Hệ điều hành
*   Phần mềm yêu cầu
*   Hiệu suất hệ thống
*   Tiêu chuẩn phần mềm
*   Card mạng
*   Tiêu chuẩn mã nguồn
*   Tiêu chuẩn báo cáo

## Index

(Chỉ mục)

Các khái niệm và vị trí xuất hiện.

## Appendix - User Interface Specifications

Mẫu giao diện người dùng tương ứng với từng usecase.
