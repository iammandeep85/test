      <template>
      <f7-page name="home" class="test">
      <!-- Upper Part -->
      <div class="header_part">
        <f7-block>
            <f7-row>
              <f7-icon ios="f7:sort" aurora="f7:sort" md="material:sort"></f7-icon>
              <f7-icon ios="f7:layers" aurora="f7:layers" md="material:layers" class="icon_box">
              </f7-icon>
            </f7-row>
        </f7-block>
        <f7-block-title class="login_title" medium>LOGIN</f7-block-title>
        <f7-block>
          <f7-list class="login_input" inset>
            <f7-row>
              <f7-col>
              <f7-list-input
                  type="text"
                  class="login_input1"
                  placeholder="@username"
                  clear-button
                ></f7-list-input>
                </f7-col>
            </f7-row>
            <f7-row>
              <f7-col><f7-list-input
                type="password"
                class="login_input1"
                placeholder="password"
                clear-button
              ></f7-list-input>
              </f7-col>
            </f7-row>
            <f7-row>
              <f7-col>
              <f7-button class="login_btn">GO !</f7-button>
                </f7-col>
            </f7-row>
          </f7-list>
        </f7-block>
      </div>
      <!-- Center Image Icon Part -->

      <f7-fab  position="fab-center-center" slot="fixed" color="white">
        <img width="35" src="../assets/img/chevron-down-512.png" />
        </f7-fab>
        <!-- Lower Part -->

      <div class="footer_part">
      <f7-block-footer class="footer_style">
        <f7-block>
        <f7-row>
          <f7-col>
            <f7-button icon="icon-home" class="social_btn" fill color="blue">Login With facebook
            </f7-button>
          </f7-col>
        </f7-row>
        <br />
          <f7-row>
            <f7-col>
            <f7-button icon="icon-home" class="social_btn" fill color="skyblue">Login With Twitter
            </f7-button>
              </f7-col>
          </f7-row>
          <f7-row class="footer_end">
            <f7-col>
            <p>Create an Account</p>
            <hr />
            <p>ABOUT|CONTACT</p>

              </f7-col>
          </f7-row>
          <f7-row class="footer_end">
            <f7-col>
                </f7-col>
          </f7-row>

        </f7-block>
      </f7-block-footer>
      </div>
      </f7-page>
      </template>
      <style lang="scss" scoped>
      .header_part{
        height:50%;
        background:linear-gradient(to right, rgba(47,250,220,0.9),rgba(114,218,240,0.7));
        overflow:hidden;
      }
      .footer_part{
        height:50%;
        overflow:hidden;
        scroll:none;
        opacity:none;
        background-color: rgb(239,242,247);
      }
      .icon_box
      {
        box-shadow: 7px -7px 0px 0px rgba(0, 0, 0, 0.75);
        border-radius:5px;
      }
      .login_title
      {
      text-align:center;
      color:white;
      }
      .login_block{
            width:50%;
            margin:0 auto;
            background-color:none;
            color:none;
      }
      .login_input
      {
          width:70%;
          margin:0 auto;
          opacity:1.0;
          padding:0px 0px 0px 0px;
          list-style:none;
          color: white;
      }
      .login_btn{
            width:50%;
            text-align: center;
            margin: 0 auto;
            border:1px solid white;
            color:white;
            }
    .footer_style
            {
            opacity:none !important;
            margin-top:50px;
            }
            .footer_end{
            top:80px;
            text-align: center;
            position: relative;
            width:80%;
            margin:0 auto;
            }
            .social_btn
            {
            width:90%;
            margin:0 auto;
            }

      </style>
