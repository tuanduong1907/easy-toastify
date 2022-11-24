<!-- Gắn vào sau thẻ mở body hoặc trước thẻ đóng body -->
<div id="toast"></div>

<!-- Sử dụng -->
<script>
    function showSuccessToast() {
        toast({
            title: "Thành công!",
            message: "Đăng ký tài khoản thành công. Hãy đăng nhập tại đây",
            type: "success",
            duration: 2000
        });
    }
</script>