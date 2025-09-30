

<img src="스크린샷 2025-09-30 120210.png">


상품 (Product) API

| 기능 | HTTP Method | URI |
| :--- | :--- | :---|
| 상품 정보 등록 | `POST` | `/products` |
| 상품 목록 조회 | `GET` | `/products` |
| 개별 상품 상세 조회 | `GET` | `/products/{productId}` |
| 상품 정보 수정 | `PATCH` | `/products/{productId}` |
| 상품 삭제 | `DELETE` | `/products/{productId}` |

<br>

## 주문 (Order) API

| 기능 | HTTP Method | URI |
| :--- | :--- | :--- |
| 주문 정보 생성 | `POST` | `/orders` |
| 주문 목록 조회 | `GET` | `/orders` |
| 개별 주문 상세 조회 | `GET` | `/orders/{orderId}` |
| 주문 취소 | `DELETE` | `/orders/{orderId}` |
