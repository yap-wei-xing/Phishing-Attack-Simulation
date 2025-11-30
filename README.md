# Phishing-Attack-Simulation

<!DOCTYPE html>
<html>
<head>
<style>
  /* General Reset */
  body { margin: 0; padding: 0; font-family: 'Helvetica', 'Arial', sans-serif; background-color: #f4f4f4; }
  
  /* Container */
  .email-container {
    max-width: 600px;
    margin: 0 auto;
    background-color: #ffffff;
    border: 1px solid #dddddd;
    box-shadow: 0px 2px 5px rgba(0,0,0,0.05);
  }

  /* Header */
  .header {
    background-color: #d9534f; /* Alert Red color to induce panic */
    color: #ffffff;
    padding: 20px;
    text-align: center;
  }

  /* Body Content */
  .content { padding: 30px; color: #333333; line-height: 1.6; }

  /* The Phishing Button */
  .btn-phish {
    display: inline-block;
    padding: 12px 24px;
    background-color: #0056b3; /* Official-looking blue */
    color: #ffffff !important;
    text-decoration: none;
    border-radius: 4px;
    font-weight: bold;
    margin-top: 20px;
  }

  /* Footer */
  .footer {
    background-color: #eeeeee;
    padding: 15px;
    text-align: center;
    font-size: 12px;
    color: #888888;
  }

  /* Educational Highlight Class (For your research display) */
  .tactic-note {
    font-size: 10px;
    color: red;
    border: 1px dashed red;
    padding: 2px;
    background: #fff0f0;
    display: block; /* Change to 'none' to hide research notes */
    margin-bottom: 5px;
  }
</style>
</head>
<body>

  <div class="email-container">
    
    <div class="header">
      <h1>Security Alert</h1>
    </div>

    <div class="content">
      <span class="tactic-note">[Research Note: Generic Greeting used to bypass personalization filters]</span>
      <p><strong>Dear Customer,</strong></p>

      <p>We detected an unauthorized login attempt to your account from an unrecognized device in <strong>Lagos, Nigeria</strong>.</p>
      
      <p>To protect your funds and data, we have temporarily suspended your account access.</p>

      <p>You must verify your identity within <strong>24 hours</strong> or your account will be permanently locked.</p>
      
      <span class="tactic-note">[Research Note: Hovering this link would reveal a mismatched URL]</span>
      <center>
        <a href="http://www.fake-site-example.com/login" class="btn-phish">Verify Identity Now</a>
      </center>
      
      <p style="margin-top: 30px; font-size: 14px;">
        If you did not make this request, please ignore this email.<br>
        <em>Security Team</em>
      </p>
    </div>

    <div class="footer">
      &copy; 2025 Global Secure Corp. All rights reserved.<br>
      <a href="#" style="color: #888;">Privacy Policy</a> | <a href="#" style="color: #888;">Unsubscribe</a>
    </div>
  </div>

</body>
</html>
