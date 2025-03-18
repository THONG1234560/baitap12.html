<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>12-5-5.html</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            white-space: pre;
        }
    </style>
</head>
<body>
    <script>
        function tinhLaiNganHang(tienGoc, soThang, laiSuat) {
            laiSuat /= 100;
            const soTienCuoi = tienGoc * Math.pow((1 + laiSuat), soThang);
            return soTienCuoi;
        }

        const tienGoc = parseFloat(prompt("Nhập số tiền ban đầu (VNĐ):"));
        const soThang = parseInt(prompt("Nhập số tháng cho vay:"));
        const laiSuat = parseFloat(prompt("Nhập lãi suất hàng tháng (%):"));

        const soTienCuoi = tinhLaiNganHang(tienGoc, soThang, laiSuat);
        alert(`Số tiền cuối cùng sau ${soThang} tháng là: ${soTienCuoi.toFixed(2)} VNĐ`);
        console.log(`Số tiền cuối cùng sau ${soThang} tháng là: ${soTienCuoi.toFixed(2)} VNĐ`);
    </script>
</body>
</html>
