# Chương trình tính toán biểu thức hậu tố

## Trình bày: 

- ### Họ và tên: Lê Quốc Hưng
- ### MSSV: 23120270

## Sản phẩm được build trên Visual Studio 2022, ở chế độ Release phiên bản x64.

## Những yêu cầu đã đạt được:

- ### ✔️ Chương trình đã chạy được trên máy sinh viên.
- ### ✔️ Chương trình đã được scan virus.

## Mô tả chương trình:
- ### Hàm tính toán chia dư Modulo (%):
     ### Mã nguồn:

    ```cpp
    double calculateDoubleModulo(double d1, double d2)
    {
        return d1 - trunc(d1 / d2) * d2;
        // Hàm được thực hiện với d2 khác 0
    }
    ```

    Hàm trunc(x) được sử dụng với mục đích cắt bớt đi phần thập phân của x và trả về kiểu dữ liệu double.

    #### ___Ví dụ___:

    Với d1 = 5.02, d2 = 2.19, phép tính được thực hiện như sau:

    $$ x = \frac{d1}{d2} \approx 2.29224 $$

    Suy ra trunc(x) = 2 (Kiểu dữ liệu double)
    
    Tiếp theo ta có: 
    $$ y = trunc(x) \times d2 = 2 \times 2.19 = 4.38 $$

    Cuối cùng ta thu được kết quả:
    $$ d1 - y = 5.02 - 4.38 = 0.64 $$

    Thật vậy:
    $$ 5.02 = 2 \times 2.19 + 0.64 $$

    Từ đó ta thu được:
    $$ 5.02 \equiv 0.64 \mod 2.19 $$

- ### Hàm tính toán toán tử mũ (^):
    Trong chương trình này, phép toán mũ được sử dụng từ hàm pow trong thư viện "math.h" nên không có hàm mô tả.

## Cách chạy chương trình:

#### 🔗 Tutorial: [YouTube](https://youtu.be/lsxWlTt65Rs)
