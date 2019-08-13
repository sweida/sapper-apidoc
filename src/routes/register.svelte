<svelte:head>
	<title>注册账号</title>
</svelte:head>

<script>
import Bg from './Bg.svelte'

</script>

  <main>
    <section class="section section-shaped section-lg my-0">
      <Bg></Bg>
      <div class="container pt-lg-md">
        <div class="row justify-content-center">
          <div class="col-lg-5">
            <div class="card bg-secondary shadow border-0">
              <div class="card-header bg-white pb-3">
                <div class="text-muted text-center">
                  <small>注册新账号</small>
                </div>
                <!-- <div class="text-center">
                  <a href="javascript:;" class="btn btn-neutral btn-icon mr-4">
                    <span class="btn-inner--icon">
                      <img src="../assets/img/icons/common/github.svg" alt="">
                    </span>
                    <span class="btn-inner--text">Github</span>
                  </a>
                  <a href="javascript:;" class="btn btn-neutral btn-icon">
                    <span class="btn-inner--icon">
                      <img src="../assets/img/icons/common/google.svg" alt="">
                    </span>
                    <span class="btn-inner--text">Google</span>
                  </a>
                </div> -->
              </div>
              <div class="card-body px-lg-5 py-lg-5">
                <!-- <div class="text-center text-muted mb-4">
                  <small>注册新账号</small>
                </div> -->
                <form role="form">
                  <div class="form-group">
                    <div class="input-group input-group-alternative mb-3">
                      <div class="input-group-prepend">
                        <span class="input-group-text"><i class="ni ni-hat-3"></i></span>
                      </div>
                      <input class="form-control" placeholder="昵称" type="text">
                    </div>
                  </div>
                  <div class="form-group">
                    <div class="input-group input-group-alternative mb-3">
                      <div class="input-group-prepend">
                        <span class="input-group-text"><i class="ni ni-email-83"></i></span>
                      </div>
                      <input class="form-control" placeholder="翼支付邮箱" type="email">
                    </div>
                  </div>
                  <div class="form-group">
                    <div class="input-group input-group-alternative">
                      <div class="input-group-prepend">
                        <span class="input-group-text"><i class="ni ni-lock-circle-open"></i></span>
                      </div>
                      <input class="form-control" placeholder="密码" type="password">
                    </div>
                  </div>
                  <div class="form-group">
                    <div class="input-group input-group-alternative">
                      <div class="input-group-prepend">
                        <span class="input-group-text"><i class="ni ni-lock-circle-open"></i></span>
                      </div>
                      <input class="form-control" placeholder="确认密码" type="password">
                    </div>
                  </div>
                  <!-- <div class="text-muted font-italic">
                    <small>password strength:
                      <span class="text-success font-weight-700">strong</span>
                    </small>
                  </div> -->
                  <!-- <div class="row my-4">
                    <div class="col-12">
                      <div class="custom-control custom-control-alternative custom-checkbox">
                        <input class="custom-control-input" id="customCheckRegister" type="checkbox">
                        <label class="custom-control-label" for="customCheckRegister">
                          <span>I agree with the
                            <a href="javascript:;">Privacy Policy</a>
                          </span>
                        </label>
                      </div>
                    </div>
                  </div> -->
                  <div class="text-center">
                    <button type="button" class="btn btn-primary m-4">注册账号</button>
                  </div>
                  <div class="text-muted text-center font-italic">
                    <small>已有账号？
                      <a href="login" class="text-success font-weight-700">去登录</a>
                      <!-- <span class="text-success font-weight-700">去登录</span> -->
                    </small>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>




<style>
form {
	padding: 20px;
}

</style>