<svelte:head>
	<title>新增api接口</title>
</svelte:head>

<script>
	import Alert from './Alert.svelte';
	let scoops = 1;
	let success = false
	function show() {
		success = true
	}

	// let flavours = ['Mint choc chip'];

	// let menu = [
	// 	'Cookies and cream',
	// 	'Mint choc chip',
	// 	'Raspberry ripple'
	// ];

	// function join(flavours) {
	// 	if (flavours.length === 1) return flavours[0];
	// 	return `${flavours.slice(0, -1).join(', ')} and ${flavours[flavours.length - 1]}`;
	// }
</script>
<Alert success={success}/>
<main>

	<nav class="navbar navbar-expand-lg navbar-dark bg-default">
		<div class="container">
			<a class="navbar-brand" href="javascript:;">天翼保理api接口文档</a>
			<a class="navbar-brand" href="/">api接口列表</a>
			<a class="navbar-brand" href="addapi">新增接口</a>
			<!-- <a href="/" class="btn btn-3 btn-icon btn-info">
			<span class="btn-inner--icon">
				<i class="ni ni-atom"></i>
			</span>
			<span class="btn-inner--text">api接口列表</span>
		</a> -->
			<!-- <button type="button" class="btn btn-3 btn-icon btn-primary">
			<span class="btn-inner--icon">
				<i class="ni ni-atom"></i>
			</span>
			<span class="btn-inner--text">新增接口</span>
		</button> -->
			<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar-default"
				aria-controls="navbar-default" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon">333</span>
			</button>
			<div class="collapse navbar-collapse" id="navbar-default">
				<div class="navbar-collapse-header">
					<div class="row">
						<div class="col-6 collapse-brand">
							<a href="./index.html">
								<img alt="" src="./assets/img/brand/blue.png">
							</a>
						</div>
						<div class="col-6 collapse-close">
							<button type="button" class="navbar-toggler" data-toggle="collapse"
								data-target="#navbar-default" aria-controls="navbar-default" aria-expanded="false"
								aria-label="Toggle navigation">
								<span></span>
								<span></span>
							</button>
						</div>
					</div>
				</div>
				<ul class="navbar-nav ml-lg-auto">
					<li class="nav-item">
						<a class="nav-link nav-link-icon" href="javascript:;">
							<i class="ni ni-favourite-28"></i>
							<span class="nav-link-inner--text d-lg-none">Discover</span>
						</a>
					</li>
					<li class="nav-item">
						<a class="nav-link nav-link-icon" href="javascript:;">
							<i class="ni ni-notification-70"></i>
							<span class="nav-link-inner--text d-lg-none">Profile</span>
						</a>
					</li>
					<li class="nav-item dropdown">
						<a class="nav-link nav-link-icon" href="javascript:;" id="navbar-default_dropdown_1"
							role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							<i class="ni ni-circle-08"></i>
							<span class="nav-link-inner--text d-lg-none">Settings</span>
						</a>
						<div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbar-default_dropdown_1">
							<a class="dropdown-item" href="javascript:;">
								<i class="ni ni-diamond"></i>
								查看我添加的接口</a>
							<a class="dropdown-item" href="javascript:;">
								<i class="ni ni-settings-gear-65"></i>
								修改密码
							</a>
							<div class="dropdown-divider"></div>
							<a class="dropdown-item" href="javascript:;">
								<i class="ni ni-spaceship"></i>
								退出登录
							</a>
						</div>
					</li>
				</ul>
			</div>
		</div>
	</nav>


	<div class="header bg-primary pb-6">
		<div class="container container-fluid">
			<div class="header-body">
				<div class="row align-items-center py-4">
					<div class="col-lg-6 col-7">
						<h6 class="h2 text-white d-inline-block mb-0">Examples</h6>
						<nav aria-label="breadcrumb" class="d-none d-md-inline-block ml-md-4">
							<ol class="breadcrumb breadcrumb-links breadcrumb-dark">
								<li class="breadcrumb-item"><a
										href="https://argon-dashboard-pro-laravel.creative-tim.com/dashboard"><i
											class="fas fa-home"></i></a></li>
								<li class="breadcrumb-item"><a
										href="https://argon-dashboard-pro-laravel.creative-tim.com/item">Item
										Management</a></li>
								<li class="breadcrumb-item active" aria-current="page">Add Item</li>
							</ol>
						</nav>
					</div>
					<div class="col-lg-6 col-5 text-right">
						<a href="#" class="btn btn-sm btn-neutral">New</a>
						<a href="#" class="btn btn-sm btn-neutral">Filters</a>
					</div>
				</div>
			</div>
		</div>
	</div>


	<div class="container container-fluid mt--6 mb-5">
		<div class="row">
			<div class="col-xl-12 order-xl-1">
				<div class="card">
					<div class="card-header">
						<div class="row align-items-center">
							<div class="col-8">
								<h5 class="mb-0">添加api文档</h5>
							</div>
							<div class="col-4 text-right">
								<a href="#" onClick="javascript :history.back(-1);" class="btn btn-sm btn-primary">后退</a>
							</div>
						</div>
					</div>
					<div class="card-body">
						<form>
							<div class="form-group row">
								<label for="example-text-input"
									class="col-md-2 col-form-label form-control-label">api地址</label>
								<div class="col-md-10">
									<input class="form-control" type="text" value="" id="example-text-input" required>
								</div>
							</div>
							<div class="form-group row">
								<label for="example-search-input"
									class="col-md-2 col-form-label form-control-label">请求方式</label>
								<div class="col-md-5">
									<ul class="nav nav-pills nav-fill flex-column flex-md-row" id="tabs-text"
										role="tablist">
										<li class="nav-item">
											<a class="nav-link btn-outline-success active" data-toggle="tab"
												href="javascript:;" role="tab" aria-selected="true">POST</a>
										</li>
										<li class="nav-item">
											<a class="nav-link btn-outline-info" data-toggle="tab" href="javascript:;"
												role="tab" aria-selected="false">GET</a>
										</li>
										<li class="nav-item">
											<a class="nav-link btn-danger" data-toggle="tab" href="javascript:;"
												role="tab" aria-selected="false">DELETE</a>
										</li>
										<li class="nav-item">
											<a class="nav-link btn-warning" data-toggle="tab" href="javascript:;"
												role="tab" aria-selected="false">PUT</a>
										</li>
									</ul>
									<!-- <div class="btn-group btn-group-toggle" data-toggle="buttons">
										<label class="btn btn-secondary active">
										<input type="radio" name="options" id="option1" autocomplete="off" checked="" /> POST
										</label>
										<label class="btn btn-secondary">
										<input type="radio" name="options" id="option2" autocomplete="off" /> GET
										</label>
										<label class="btn btn-secondary">
										<input type="radio" name="options" id="option3" autocomplete="off" /> DELETE
										</label>
										<label class="btn btn-secondary">
										<input type="radio" name="options" id="option3" autocomplete="off" /> PUT
										</label>
									</div> -->
									<!-- <label class="mr-3">
										<input type=radio bind:group={scoops} value={1} >
										Post
									</label>

									<label class="mr-3">
										<input type=radio bind:group={scoops} value={2}>
										Get
									</label>

									<label class="mr-3">
										<input type=radio bind:group={scoops} value={3}>
										Delete
									</label>

									<label class="mr-3">
										<input type=radio bind:group={scoops} value={4}>
										Put
									</label> -->
									<!-- <div class="custom-control custom-radio custom-control-inline">
										<input type="radio" id="customRadioInline1" name="customRadioInline1" class="custom-control-input">
										<label class="custom-control-label" for="customRadioInline1">post</label>
									</div>
									<div class="custom-control custom-radio custom-control-inline">
										<input type="radio" id="customRadioInline2" name="customRadioInline1" class="custom-control-input">
										<label class="custom-control-label" for="customRadioInline2">get</label>
									</div>
									<div class="custom-control custom-radio custom-control-inline">
										<input type="radio" id="customRadioInline3" name="customRadioInline1" class="custom-control-input">
										<label class="custom-control-label" for="customRadioInline3">delete</label>
									</div>
									<div class="custom-control custom-radio custom-control-inline">
										<input type="radio" id="customRadioInline4" name="customRadioInline1" class="custom-control-input">
										<label class="custom-control-label" for="customRadioInline4">put</label>
									</div> -->
								</div>
							</div>
							<div class="form-group row">
								<label for="example-email-input"
									class="col-md-2 col-form-label form-control-label">描叙</label>
								<div class="col-md-10">
									<input class="form-control" type="email" value="" id="example-email-input">
								</div>
							</div>
							<div class="form-group row">
								<label for="example-url-input"
									class="col-md-2 col-form-label form-control-label">所属项目</label>
								<div class="col-md-10">
									<input class="form-control" type="url" value="" id="example-url-input" required>
								</div>
							</div>
							<div class="form-group row">
								<label for="example-tel-input"
									class="col-md-2 col-form-label form-control-label">请求参数</label>
								<div class="col-md-10">
									<textarea class="form-control" id="exampleFormControlTextarea1" rows="6"></textarea>
									<!-- <input class="form-control" type="tel" value="40-(770)-888-444" id="example-tel-input"> -->
								</div>
							</div>
							<div class="form-group row">
								<label for="example-password-input"
									class="col-md-2 col-form-label form-control-label">返回值</label>
								<div class="col-md-10">
									<textarea class="form-control" id="exampleFormControlTextarea1" rows="6"></textarea>
									<!-- <input class="form-control" type="password" value="password" id="example-password-input"> -->
								</div>
							</div>

							<div class="text-center m-auto col-md-3">
								<button class="btn btn-success btn-block mb-3" type="button" on:click={show}>提 交</button>
							</div>

						</form>
					</div>
				</div>
			</div>
		</div>


	</div>


</main>

<style>
	main {
		background: #f8f9fe;
	}

	.mt--6 {
		margin-top: -4.5rem;
	}

	.pb-6 {
		padding-bottom: 4.5rem;
	}

	.card {
		border: 0;
		box-shadow: 0 0 2rem 0 rgba(136, 152, 170, .15);
	}
</style>