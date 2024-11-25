# Be-Kim
Block all Windows 10 apps from using internet except one

Be Kim Jung Un, The supreme leader of North Korea! Just by blocking all internet traffic in your Windows 10 except one app. In this case, you will become number one man in the world. let's go:

* Open **Windows Defender Firewall**.
* Click on **Advanced settings** in the left panel, A new window will be opened.
* Click on **Windows Defender Firewall Properties** in the bottom of **Overview** section, A new window will be opened.
* Under the each **Domain Profile** , **Private Profile** and **Public Profile** tabs, choose **Block** option from drop-down menu for **Inbound connections** and **Outbound connections**.
* Click on **Apply** and **Ok** button, Current window will be closed and all internet traffic in your PC or laptop will be blocked.
* In the **Windows Defender Firewall with Advanced Security** window which opened before, Click on **Outbound Rules** in the left panel.
* In the right panel click on **New Rule**, A new window will be opened.
* Choose **Program** radio button and click on **Next** button, Then choose **This program path** radio button and click on **Browse** button to locate the app which you want to allow it, Then click on **next** button, Then choose **Allow the connection** radio button and click on **next** button, Then leave the choices unchanged and click on **next** button, Then type a name in the **Name** text field for your rule and click on **Finish** button. The current window will be closed and only your choosed app has access to the internet.

It's tested and worked fine for me. 

Only allowed app in my Windows 10: `Bitvise SSH Client`
