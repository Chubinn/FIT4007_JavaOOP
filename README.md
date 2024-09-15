# FIT4007_JavaOOP
Lập trình hướng đối tượng với java (Đại Nam universiry)
public class Main {
    public static void main(String[] args) {
        // Khởi tạo biến tổng để lưu tổng các số chia hết cho 7
        int tong = 0;

        // In ra thông báo bắt đầu quá trình tính toán
        System.out.println("Đang tính tổng các số là bội số của 7 từ 1 đến 100...");

        // Lặp qua tất cả các số từ 1 đến 100
        for (int i = 1; i <= 100; i++) {
            // Kiểm tra nếu số i là bội số của 7
            if (i % 7 == 0) {
                // Nếu đúng, thêm i vào tổng
                tong += i;
                // In ra số hiện tại là bội số của 7
                System.out.println(i + " là bội số của 7, tổng hiện tại: " + tong);
            }
        }

        // Sau khi hoàn thành, in ra tổng cuối cùng
        System.out.println("Tổng các số là bội số của 7 từ 1 đến 100 là: " + tong);
    }
}
