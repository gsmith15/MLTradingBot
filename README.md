# TraderBot
Build a trader bot which looks at sentiment of live news events and trades appropriately. 

# Startup 🚀
1. Create a virtual environment `conda create -n trader python=3.10` 
2. Activate it `conda activate trader`
3. Install initial deps `pip install lumibot timedelta alpaca-trade-api==3.1.1`
4. Install transformers and friends `pip install torch torchvision torchaudio transformers` 
5. Update the `API_KEY` and `API_SECRET` with values from your Alpaca account 
6. Run the bot `python tradingbot.py`

<p>N.B. Torch installation instructions will vary depending on your operating system and hardware. See here for more: 
<a href="pytorch.org/">PyTorch Installation Instructions</a></p>

If you're getting an SSL error when you attempt to call out to the Alpaca Trading api, you'll need to install the required SSL certificates into your machine.
1. Download the following intermediate SSL Certificates, these are required to communicate with Alpaca
* https://letsencrypt.org/certs/lets-encrypt-r3.pem 
* https://letsencrypt.org/certs/isrg-root-x1-cross-signed.pem 
2. Once downloaded, change the file extension of each file to `.cer` 
3. Double click the file and run through the wizard to install it, use all of the default selections. 

</br>
# Other References 🔗

<p>-<a href="github.com/Lumiwealth/lumibot)">Lumibot</a>:trading bot library, makes lifecycle stuff easier .</p>

# Who, When, Why?

👨🏾‍💻 Author: Nick Renotte <br />
📅 Version: 1.x<br />
📜 License: This project is licensed under the MIT License </br>

# Screenshots
![Screenshot 2024-05-08 171019](https://github.com/gsmith15/MLTradingBot/assets/23180540/e4d517d8-da68-4877-a95a-e150bc24d392)
![Screenshot 2024-05-08 171031](https://github.com/gsmith15/MLTradingBot/assets/23180540/c5c5e22c-ba8f-4548-94d8-7affed428173)
![Screenshot 2024-05-08 154759](https://github.com/gsmith15/MLTradingBot/assets/23180540/e77506e0-8944-412b-b828-b352ac79c095)
