<svelte:head>
	<title>忘记密码</title>
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
              <div class="card-header bg-white pb-1">
                <div class="text-muted text-center mb-2">
                  <small>通过邮件重置密码</small>
                </div>
                <div class="card-body px-lg-4 py-lg-4">
                  <form role="form">
                    <div class="form-group mb-3">
                      <div class="input-group input-group-alternative">
                        <div class="input-group-prepend">
                          <span class="input-group-text"><i class="ni ni-email-83"></i></span>
                        </div>
                        <input class="form-control" placeholder="请输入注册时的邮箱地址" type="email">
                      </div>
                    </div>
                    <div class="text-center">
                      <button type="button" class="btn btn-primary mt-3">发送邮件验证码</button>
                    </div>
                  </form>
                </div>
              </div>
              <div class="card-body px-lg-5 py-lg-5">
                <!-- <div class="text-center text-muted mb-4">
                  <small>或者使用账号登录</small>
                </div> -->
                <form role="form">
                  <div class="form-group mb-3">
                    <div class="input-group input-group-alternative">
                      <div class="input-group-prepend">
                        <span class="input-group-text"><i class="ni ni-email-83"></i></span>
                      </div>
                      <input class="form-control" placeholder="验证码" type="number">
                    </div>
                  </div>
                  <div class="form-group">
                    <div class="input-group input-group-alternative">
                      <div class="input-group-prepend">
                        <span class="input-group-text"><i class="ni ni-lock-circle-open"></i></span>
                      </div>
                      <input class="form-control" placeholder="新密码" type="password">
                    </div>
                  </div>
                  <div class="form-group">
                    <div class="input-group input-group-alternative">
                      <div class="input-group-prepend">
                        <span class="input-group-text"><i class="ni ni-lock-circle-open"></i></span>
                      </div>
                      <input class="form-control" placeholder="确认新密码" type="password">
                    </div>
                  </div>
                  <!-- <div class="custom-control custom-control-alternative custom-checkbox">
                    <input class="custom-control-input" id=" customCheckLogin" type="checkbox">
                    <label class="custom-control-label" for=" customCheckLogin">
                      <span>记住密码</span>
                    </label>
                  </div> -->
                  <div class="text-center">
                    <button type="button" class="btn btn-primary my-4">确 认</button>
                  </div>
                </form>
              </div>
            </div>
            <div class="row mt-3">
              <div class="col-6">
                <!-- <a href="forgotpassword" class="text-light">
                  <small>忘记密码?</small>
                </a> -->
              </div>
              <div class="col-6 text-right">
                <a href="login" class="text-light">
                  <small>去登录</small>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

