<template>
  <f7-page>
    <div class="vh-100 d-flex flex-column justify-content-center">
      <f7-block>
        <f7-list form>
          <f7-list-input label="手機號碼"
                         type="text"
                         name="userName"
                         placeholder="手機號碼"></f7-list-input>
          <f7-list-input label="密碼"
                         type="password"
                         name="password"
                         placeholder="密碼"></f7-list-input>
          <f7-row>
            <f7-col width="60">
              <f7-checkbox/>
              <span class="button"
                    style="display: inline;">自動登入</span>
            </f7-col>
            <f7-col width="15">
              <a href="/signup">註冊</a>
            </f7-col>
            <f7-col width="25">
              <f7-button small>忘記密碼</f7-button>
            </f7-col>
          </f7-row>
        </f7-list>
        <f7-list>
          <f7-button class="bg-default fw-bold btn-lg shadow-sm mb-4"
                     fill
                     round
                     login-screen-open="#my-login-screen">登入
          </f7-button>
        </f7-list>
      </f7-block>
    </div>
  </f7-page>
</template>
