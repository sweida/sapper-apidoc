

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>


<script>
	import { onMount } from 'svelte';

	let photos = [];

	onMount(async () => {
		const res = await fetch(`http://localhost:8800/api/v2/apidoc/list`);
		console.log(res, 44444)
		photos = await res.json();
	});

</script>



<nav class="navbar navbar-expand-lg navbar-dark bg-default">
	<div class="container">
		<a class="navbar-brand" href="javascript:;">天翼保理api接口文档</a>
		<a href="/" class="btn btn-3 btn-icon btn-info">
			<span class="btn-inner--icon">
				<i class="ni ni-atom"></i>
			</span>
			<span class="btn-inner--text">api接口列表</span>
		</a>
		<a href="addapi" class="btn btn-3 btn-icon btn-primary">
			<span class="btn-inner--icon">
				<i class="ni ni-atom"></i>
			</span>
			<span class="btn-inner--text">新增接口</span>
		</a>
		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar-default" aria-controls="navbar-default" aria-expanded="false" aria-label="Toggle navigation">
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
				<button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbar-default" aria-controls="navbar-default" aria-expanded="false" aria-label="Toggle navigation">
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
			<a class="nav-link nav-link-icon" href="javascript:;" id="navbar-default_dropdown_1" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
				<i class="ni ni-circle-08"></i>
				<span class="nav-link-inner--text d-lg-none">Settings</span>
			</a>
			<div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbar-default_dropdown_1">
				<a class="dropdown-item" href="javascript:;">
					<i class="ni ni-planet"></i>
					我添加的接口</a>
				<a class="dropdown-item" href="javascript:;">
					<i class="ni ni-settings-gear-65"></i>
					修改密码
				</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="javascript:;">
					<i class="ni ni-user-run"></i>
					退出登录
				</a>
			</div>
			</li>
		</ul>
		</div>
	</div>
</nav>



<div class="container">

	<div class="post border border-success my-3 ">
		<div class="px-3 py-2" data-toggle="collapse" data-target="#collapseOne1" aria-expanded="true" aria-controls="collapseOne">
			<button class="btn btn-sm btn-success" type="button">post</button>
			<span class="font-weight-bold mr-3">/apply</span>
			<small>提额接口</small>
			<button type="button" class="close" data-dismiss="alert" aria-label="Close">
				<i class="fa fa-code text-success"></i>
			</button>
		</div>
		<div id="collapseOne1" class="border-top border-success collapse show" >
			<div class="card-body">
				<div class="row mb-3 border-bottom">
					<div class="col-2">
						<span>params</span>
						<p>(请求参数)</p>
					</div>
					<div class="col-10">
						<!-- <div class="card bg-gradient-dark"></div> -->
						<div class="alert alert-default">
					
							<blockquote class="blockquote text-white p-2 mb-0">
								<footer class="blockquote-footer text-danger">Someone famous in <cite title="Source Title">Source Title</cite></footer>
							</blockquote>
						</div>
					</div>
				</div>
				<div class="row ">
					<div class="col-2">
						<span>Responses</span>
						<p>(返回值)</p>
					</div>
					<div class="col-10">
						<div class="alert alert-default">
							<blockquote class="blockquote text-white p-2 mb-0">
								<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
								<footer class="blockquote-footer text-danger">Someone famous in <cite title="Source Title">Source Title</cite></footer>
							</blockquote>
						</div>
					</div>
				</div>
				<div class="text-right">
					<button type="button" class="btn btn-sm btn-primary "> 
						<span class="btn-inner--icon">
							<i class="ni ni-planet"></i>
						</span>
						<span class="btn-inner--text">编 辑 </span>
					</button>
				</div>
			</div>
		</div>
	</div>
	<div class="get border border-info my-3">
		<div class="px-3 py-2" data-toggle="collapse" data-target="#collapseOne2" aria-expanded="true" aria-controls="collapseOne">
			<button class="btn btn-sm btn-info" type="button">get</button>
			<span class="font-weight-bold mr-3">/apply</span>
			<small>提额接口</small>
			<button type="button" class="close" data-dismiss="alert" aria-label="Close">
				<i class="fa fa-angle-right text-info"></i>
			</button>
		</div>
		<div id="collapseOne2" class="border-top border-info collapse" >
			<div class="card-body">
			<p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</p>
			</div>
		</div>
	</div>
	<div class="delete border border-danger my-3">
		<div class="px-3 py-2" data-toggle="collapse" data-target="#collapseOne3" aria-expanded="true" aria-controls="collapseOne">
			<button class="btn btn-sm btn-danger" type="button">delete</button>
			<span class="font-weight-bold mr-3">/apply</span>
			<small>提额接口</small>
			<button type="button" class="close" data-dismiss="alert" aria-label="Close">
				<i class="fa fa-angle-right text-danger"></i>
			</button>
		</div>
		<div id="collapseOne3" class="border-top border-danger collapse" >
			<div class="card-body">
			<p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</p>
			</div>
		</div>
	</div>
	<div class="put border border-warning my-3">
		<div class="px-3 py-2" data-toggle="collapse" data-target="#collapseOne4" aria-expanded="true" aria-controls="collapseOne">
			<button class="btn btn-sm btn-warning" type="button">put</button>
			<span class="font-weight-bold mr-3">/apply</span>
			<small>提额接口</small>
			<button type="button" class="close" data-dismiss="alert" aria-label="Close">
				<i class="fa fa-angle-right text-warning"></i>
			</button>
		</div>
		<div id="collapseOne4" class="border-top border-warning collapse">
			<div class="card-body">
			<p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</p>
			</div>
		</div>
	</div>


</div>


<style>
.post{
	border-radius: 5px;
	background: rgba(79, 214, 156, 0.16)
}
.get{
	border-radius: 5px;
	background: rgba(17, 205, 239, 0.16)	
}
.delete{
	border-radius: 5px;
	background: rgba(245, 54, 92, 0.16)
}
.put{
	border-radius: 5px;
	background: rgba(251, 99, 64, 0.16)	
}
</style>