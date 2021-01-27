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

truong hop SweetAlert_laravel tren lam thay doi bo cuc thi su dung link
<script src="https://cdnjs.cloudflare.com/ajax/libs/sweetalert/2.1.2/sweetalert.min.js" integrity="sha512-AA1Bzp5Q0K1KanKKmvN/4d3IRKVlv9PYgwFPvm32nPO6QS8yH1HO7LbgB1pgiOxPtfeg5zEn2ba64MUcqJx6CA==" crossorigin="anonymous"></script>

swal({
	icon: 'error',
  title: 'Oops...',
  text: 'Something went wrong!',
})
