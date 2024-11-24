# Be-Kim
Block all Windows 10 apps from using internet except one

Be Kim Jung Un, The supreme leader of North Korea! Just by blocking all internet traffic in your Windows 10 except one app. In this case, you will become number one man in the world. let's go:

* Open **Windows Defender Firewall**.
* Click on **Advanced settings** in the left panel.
* Click on **Windows Defender Firewall Properties** in the bottom of **Overview** section.
* Under the each **Domain Profile** and **Private Profile** and **Public Profile** tabs, choose **Block** option from drop-down menu for **Inbound connections** and **Outbound connections**.
* Click on **Apply** and **Ok** button, Current window will be closed and all internet traffic in your PC or laptop will be blocked.
* Now, In the **Windows Defender Firewall with Advanced Security** window in front of you which opened before, Click on **Outbound Rules** in the left panel.
* In the right panel click on **New Rule**, A new window will be opened.
* Choose **Program** radio button and click on **Next** button, Then choose **This program path** and click on **Browse** button to locate app which you want allow it, Then click on **next** button, Then choose **Allow the connection** and click on **next** button, Again click on **next** button, Then type a name in the **Name** text field for your rule and click on **Finish** button.

It's tested and worked fine for me.
