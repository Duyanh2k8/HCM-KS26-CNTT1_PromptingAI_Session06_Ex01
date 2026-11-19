# [Vận dụng chuyên sâu] Thiết kế giải pháp Prompting ứng dụng thực tế cho Ứng dụng AI trong Học tập & Nghiên cứu
## 1. Phân tích bài toán
**Tên giải pháp:** AI Study Assistant – Trợ lý AI hỗ trợ học tập và chấm bài.

**Mục đích:**

Xây dựng một giải pháp sử dụng AI để hỗ trợ sinh viên trong quá trình học tập. Hệ thống có thể giải thích kiến thức khó hiểu theo phương pháp Feynman và đánh giá bài làm dựa trên Rubric (bảng tiêu chí chấm điểm).

Thay vì phải tự tìm tài liệu, giải thích kiến thức và kiểm tra bài làm thủ công, sinh viên có thể sử dụng AI để thực hiện các công việc này nhanh hơn.

**Quy trình hoạt động:**
```mermaid
flowchart TD
    A["<b>Input</b><br/>Tài liệu học tập + Bài làm + Rubric chấm điểm"]
    B["<b>AI Study Assistant</b><br/>Phân tích dữ liệu và thực hiện 2 chức năng"]
    C["<b>Feynman Tutor</b><br/>Giải thích kiến thức dễ hiểu"]
    D["<b>Rubric Grading</b><br/>Đánh giá và chấm điểm"]
    E["<b>Output</b><br/>Bài giảng dễ hiểu + Bảng điểm + Nhận xét + Hướng cải thiện"]

    A --> B
    B --> C
    B --> D
    C,D --> E

    style A fill:#e8f0fe,stroke:#d2e3fc,color:#1f1f1f,rx:10,ry:10
    style B fill:#e6f4ea,stroke:#ceead6,color:#1f1f1f,rx:10,ry:10
    style C fill:#ffffff,stroke:#dadce0,color:#1f1f1f,rx:10,ry:10
    style D fill:#ffffff,stroke:#dadce0,color:#1f1f1f,rx:10,ry:10
    style E fill:#e6f4ea,stroke:#ceead6,color:#1f1f1f,rx:10,ry:10
```
