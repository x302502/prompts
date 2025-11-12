Tech stack:

- React
- React query
- antd
- Typescript

## Các thành phần code đã có sẵn

- Các hàm fetch: getProducts, addProduct, editProduct, deleteProduct
  - getProducts: { pageIndex: number, pageSize: number , keyword?: string}
  - addProduct: { name: string, price: number }
  - editProduct: { id: number, name: string, price: number }
  - deleteProduct: { id: number }
- Types:
  - PageRequest: { pageIndex: number, pageSize: number , keyword?: string}
  - Product: { id: number, name: string, price: number }
  - ProductResponse: { data: Product[], total: number }

## Yêu cầu

Tạo component DemoView:

- Danh sách products có phân trang
- Search products
- Add product
- Edit product
- Delete product

* Các action form đều loading lại danh sách products

Style code:

- Viết các hook thành file riêng và hạn chế xài state trong view mà chỉ xài hook
  (Có 2 khuyến nghị về file hook
  1- Có 1 hook là useProducts.ts trong đó chứa các query và mutation liên quan đến products
  2- Có 1 hook chính là useProductView.ts trong đó chứa các logic của view và 4 hook khác là useProductList (cái này chứa cả search và logic phân trang), useAddProduct, useEditProduct, useDeleteProduct trong đó chứa các logic của các form
  )

Response chat:

- Viết các file thành dạng code block
