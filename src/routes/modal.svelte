<svelte:head>
	<title>新增api接口</title>
</svelte:head>

<script>
	let scoops = 1;
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

<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
  Launch demo modal
</button>

<div class="modal fade col-xl-12" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered col-md-10" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
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
								<button class="btn btn-success btn-block mb-3" type="button">提 交</button>
							</div>

						</form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>




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