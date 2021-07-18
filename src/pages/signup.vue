<template>
  <f7-page>
    <f7-navbar back-link
               title="註冊會員資料"></f7-navbar>
    <f7-block>
      <f7-row class="input-row">
        <span>帳號(手機號碼)
          <span style="color:red;">*</span>
        </span>
        <f7-col>
          <f7-input error-message="請輸入正確手機號碼"
                    maxlength="10"
                    pattern="09\d{8}"
                    required
                    type="text"
                    validate/>
        </f7-col>
      </f7-row>
      <f7-row class="input-row">
        <f7-col width="60">
        <span>驗證碼
          <span style="color:red;">*</span>
        </span>
          <f7-input maxlength="4"
                    pattern="\d{4}"
                    required
                    type="text"
                    validate/>
        </f7-col>
        <f7-col width="40">
          <f7-button class="verify-code"
                     raised>取得驗證碼
          </f7-button>
        </f7-col>
      </f7-row>
      <f7-row class="input-row">
        <span>姓名
          <span style="color:red;">*</span>
        </span>
        <f7-col>
          <f7-input maxlength="50"
                    required
                    type="text"
                    validate/>
        </f7-col>
      </f7-row>
      <f7-row class="input-row">
        <span>密碼(至少6碼英文或數字)
          <span style="color:red;">*</span>
        </span>
        <f7-col>
          <f7-input error-message="請至少輸入6碼英文或數字"
                    pattern="[a-zA-Z0-9]{6,}"
                    required
                    type="password"
                    validate/>
        </f7-col>
      </f7-row>
      <f7-row class="input-row">
        <span>確認密碼
          <span style="color:red;">*</span>
        </span>
        <f7-col>
          <f7-input error-message="請確認與密碼相符"
                    pattern="[a-zA-Z0-9]{6,}"
                    required
                    type="password"
                    validate/>
        </f7-col>
      </f7-row>
      <f7-row class="input-row">
        <f7-col width="30">
          <f7-checkbox/>
        </f7-col>
        <f7-col width="70">
          <f7-button raised>會員條款
          </f7-button>
        </f7-col>
      </f7-row>
      <f7-row class="input-row">
        <f7-col>
          <f7-button raised>下一步
          </f7-button>
        </f7-col>
      </f7-row>
    </f7-block>
  </f7-page>
</template>
