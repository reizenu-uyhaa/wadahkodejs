---
layout: default
title: Wadahkode
description: My Portofolio
---

<div class="uk-height-large">
    <div class="uk-grid-collapse uk-child-width-expand@s" uk-grid>
    <div class="uk-card uk-card-body uk-padding-small">
        <h1 class="uk-card-title">Welcome Friends</h1>
        <p>Free registration to create a new account.</p>
    </div>
    <div class="uk-card uk-width-1-1 uk-width-1-2@m uk-card-body uk-padding-small">
        <form id="form-register">
            <div class="uk-margin">
                <div class="uk-inline">
                    <span class="uk-form-icon" uk-icon="icon: mail;"></span>
                    <input type="email" class="uk-input uk-form-width-large uk-form-medium" id="email" placeholder="Enter your email" autocomplete="off">
                </div>
            </div>
            <div class="uk-margin">
                <div class="uk-inline">
                    <span class="uk-form-icon" uk-icon="icon: lock;"></span>
                    <input type="password" class="uk-input uk-form-width-large uk-form-medium" id="password" placeholder="Password" required>
                </div>
            </div>
            <div class="uk-margin">
                <label>
                    <input type="checkbox" class="uk-checkbox" id="checkbox" checked>&nbsp;&nbsp;I agree to the terms and conditions.
                </label>
            </div>
            <div class="uk-margin">
                <button type="button" class="uk-button uk-button-primary uk-button-medium uk-width-1-1 quick-btn-register">
                      Register
                </button>
            </div>
            <!--div class="uk-margin">
                <a href="index.html">
                    <i class="fab fa-google fa-fw"></i> Login with Google
                </a>
                <a href="index.html">
                    <i class="fab fa-facebook-f fa-fw"></i> Login with Facebook
                </a>
            </div-->
        </form>
        <hr class="uk-divider-icon">
        <div class="uk-text-center">
            <!--a href="forgot-password.html">Forgot Password?</a-->
            <a href="login.html">Already have an account? Login!</a>
        </div>
    </div>
    </div>
</div>