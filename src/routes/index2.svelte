

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<nav class="navbar navbar-expand-lg navbar-dark bg-default">
	<div class="container">
		<a class="navbar-brand" href="javascript:;">天翼保理api接口文档</a>
		<button type="button" class="btn btn-3 btn-icon btn-primary">
			<span class="btn-inner--icon">
				<i class="ni ni-bag-17"></i>
			</span>
			<span class="btn-inner--text">新增接口</span>
		</button>
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
				<i class="ni ni-settings-gear-65"></i>
				<span class="nav-link-inner--text d-lg-none">Settings</span>
			</a>
			<div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbar-default_dropdown_1">
				<a class="dropdown-item" href="javascript:;">Action</a>
				<a class="dropdown-item" href="javascript:;">Another action</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="javascript:;">Something else here</a>
			</div>
			</li>
		</ul>
		</div>
	</div>
</nav>



<div class="container">

	<div class="post border border-success my-2 ">
		<div class="px-3 py-2" data-toggle="collapse" data-target="#collapseOne1" aria-expanded="true" aria-controls="collapseOne">
			<button class="btn btn-sm btn-success" type="button">post</button>
			<span class="font-weight-bold mr-3">/apply</span>
			<small>提额接口</small>
			<button type="button" class="close" data-dismiss="alert" aria-label="Close">
				<i class="fa fa-angle-right text-success"></i>
			</button>
		</div>
		<div id="collapseOne1" class="border-top border-success collapse" >
			<div class="card-body">
			<p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</p>
			</div>
		</div>
	</div>
	<div class="get border border-info my-2">
		<div class="px-3 py-2" data-toggle="collapse" data-target="#collapseOne2" aria-expanded="true" aria-controls="collapseOne">
			<button class="btn btn-sm btn-info" type="button">post</button>
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
	<div class="delete border border-danger my-2">
		<div class="px-3 py-2" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
			<button class="btn btn-sm btn-danger" type="button">post</button>
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
	<div class="put border border-warning my-2">
		<div class="px-3 py-2" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
			<button class="btn btn-sm btn-warning" type="button">post</button>
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

	<ul class="navbar-nav ml-lg-auto">
		<li class="nav-item post py-2 px-3 mb-2 mt-2">
			<div class="link pb-2" data-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample">
				<button class="btn btn-sm btn-success" type="button">post</button>
				<span class="font-weight-bold mr-3">/apply</span>
				<small>提额接口</small>
				<button type="button" class="close" data-dismiss="alert" aria-label="Close">
					<i class="fa fa-angle-right text-success"></i>
				</button>
			</div>

			<div class="collapse" id="collapseExample">
				<div>
					params
				</div>
				<div>
					Responses
				</div>
				<!-- <div class="card card-body"> -->
					Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
				<!-- </div> -->
			</div>
		</li>
		<li class="nav-item get pt-2 px-3 mb-2 mt-2">
			<div class="link pb-2">
				<button class="btn btn-sm btn-info" type="button">get</button>
				<span class="font-weight-bold mr-3">/apply</span>
				<small>提额接口</small>
				<button type="button" class="close" data-dismiss="alert" aria-label="Close">
					<i class="fa fa-angle-right text-info"></i>
				</button>
			</div>
		</li>
		<li class="nav-item delete pt-2 px-3 mb-2 mt-2">
			<div class="link pb-2">
				<button class="btn btn-sm btn-danger" type="button">delete</button>
				<span class="font-weight-bold mr-3">/apply</span>
				<small>提额接口</small>
				<button type="button" class="close" data-dismiss="alert" aria-label="Close">
					<i class="fa fa-angle-right text-danger"></i>
				</button>
			</div>
		</li>
		<li class="nav-item put pt-2 px-3 mb-2 mt-2">
			<div class="link pb-2">
				<button class="btn btn-sm btn-warning" type="button">put</button>
				<span class="font-weight-bold mr-3">/apply</span>
				<small>提额接口</small>
				<button type="button" class="close" data-dismiss="alert" aria-label="Close">
					<i class="fa fa-angle-right text-warning"></i>
				</button>
			</div>
		</li>
	</ul>
	点点滴滴
</div>


<style>
.post{
	/* border: 1px solid #4fd69c; */
	border-radius: 5px;
	background: rgba(79, 214, 156, 0.16)
}
.get{
	border: 1px solid #11cdef;
	border-radius: 5px;
	background: rgba(17, 205, 239, 0.16)	
}
.delete{
	border: 1px solid #f5365c;
	border-radius: 5px;
	background: rgba(245, 54, 92, 0.16)
}
.put{
	border: 1px solid #fb6340;
	border-radius: 5px;
	background: rgba(251, 99, 64, 0.16)	
}
.border-top{
	border-top: 1px solid #4fd69c;
}
</style>