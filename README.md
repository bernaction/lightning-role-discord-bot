# ⚡ Lightning Role Bot
Is the ultimate solution for managing Discord subscriptions using the Lightning Network! 🚀

## 🛠️ Key Features:

### 🎭 Role Management:
- Automatically assign roles to paying members.

### 🌩️ Lightning Network Payments:
- Seamless integration with Lightning wallets.

### 📜 Detailed Logs:
- Keep track of activities in a dedicated log channel.

### ⏰ Automatic Monitoring:
- Check expired subscriptions and send renewal notifications.

### 🔧 Simple Setup:
- Easy-to-use commands like `/ln_admin`.

### 🧑‍💻 Perfect for servers looking to:
- Monetize through subscriptions.<br/>
- Provide a seamless and automated subscription experience.<br/>
- Integrate with Lightning wallets, like Wallet of Satoshi.<br/>

## 📖 How to Use Lightning Role Bot
### Step 1: Accept Terms and Conditions<br/>
After installing the bot, you must accept the terms and conditions before using it.<br/>
The terms will automatically appear when you type any command.<br/>
![1-terms.png](/img/1-terms.png)<br/><br/>
Once you accept, the bot will confirm that the terms have been accepted, and you can proceed to use its features.
![2-terms-accept.png](/img/2-terms-accept.png)<br/><br/>

### Step 2: Configure the Bot with /ln_admin
Use the `/ln_admin <email-lightning> <subscription usd value>` command to configure the bot for your server. This command will let you set the Lightning wallet, subscription value, log channel, and the role that the bot will manage.<br/>
![3-ln_admin_1_roles_list.png](/img/3-ln_admin_1_roles_list.png)<br/><br/>

**Important:**

> The Lightning Role bot's role must be placed above the role it will assign to users. This ensures proper permissions to assign roles.<br/>
> The target role cannot be an externally managed role (e.g., roles provided by YouTube or Twitch integrations).<br/>

To adjust the role hierarchy:

> Go to Server Settings > Roles.<br/>
> Drag the Lightning Role bot's role above the subscriber role.<br/>
> Save the changes.<br/>

![3-ln_admin_2_roles_config_in_discord.png](/img/3-ln_admin_2_roles_config_in_discord.png)<br/><br/>

After selecting and confirming the configuration, the bot will save the settings.<br/>
![3-ln_admin_3_roles_confirm.png](/img/3-ln_admin_3_roles_confirm.png)<br/><br/>
Once the settings are saved, the bot will display a confirmation message.<br/>
![3-ln_admin_4_roles_confirmed.png](/img/3-ln_admin_4_roles_confirmed.png)<br/><br/>


### Step 3: User Subscription with `/ln_subscribe`

Users can subscribe by running the `/ln_subscribe <number>` command, where <number> represents the number of months for the subscription.<br/>
Example:
> `/ln_subscribe 1` to subscribe for 1 month.<br/>

When the user subscribes, the bot will generate a Lightning invoice and a QR code for payment.<br/>
![4-ln_subscribe-new.png](/img/4-ln_subscribe-new.png)<br/><br/>
After payment is made, the bot will confirm the payment and assign the configured role to the user.<br/>
![5-ln_subscribe-payment.png](/img/5-ln_subscribe-payment.png)<br/><br/>

### Step 4: Renewing an Active Subscription

If a user wants to extend their subscription before it expires, they can use the same `/ln_subscribe` command.<br/>
The bot will calculate the new expiration date by adding the selected duration to the current expiration.<br/>
![6-ln_subscribe-renewal.png](/img/6-ln_subscribe-renewal.png)<br/><br/>
Once the renewal payment is made, the bot will confirm the extension of the subscription.
![7-ln_subscribe-renewal-payment.png](/img/7-ln_subscribe-renewal-payment.png)<br/><br/>

## 🚀 Ready to Start?
Add the Lightning Role Bot to your server and automate everything with seamless Lightning Network payments!
[Lightning BOT on Top.GG](https://top.gg/bot/1326896087914778635)

