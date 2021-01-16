# SweetAlert_laravel

Link SweetAlert : https://sweetalert2.github.io/#download

Chèn link:
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@10"></script>

Ajax: success:function(add_form_succ){
						swal('Đăng ký thành công',
						'Mật khẩu đã được gửi vào Email của bạn!!!',
						'success');
					}

@if(Session::has('test'))
<script>
swal('Đăng ký thành công',
						'Mật khẩu đã được gửi vào Email của bạn!!!',
						'success');
</script>
@endif
