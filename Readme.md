<!-- Gắn vào trước thẻ đóng body hoặc sau thẻ mở body-->
<div id="toast"></div>

<!-- Ví dụ -->
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