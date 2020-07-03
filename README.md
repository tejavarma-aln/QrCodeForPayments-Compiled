# QrCode For Payments-Compiled
Generate QR Code in Sales Invoice for making payments



**Requirements:**

1) Microsoft.net framework version 4

2) .Net Framework 4.x.x

3) Download/Clone all the files (PaymentsQr.dl,QrCoder.dll,Payment QR.tcp)

You can Download from here : https://dotnet.microsoft.com/download/dotnet-framework/net40

**Get Started and Registering DLL**

Open CMD in administrator Mode (Elevated mode)

    For 64 Bit
Type cd C:\Windows\Microsoft.NET\Framework64\v4.0.30319 ;; change directory

    For 32 Bit
Type cd C:\Windows\Microsoft.NET\Framework\v4.0.30319 ;; change directory

Type regasm PaymentsQr.dll /codebase ;;Give Full path of the PaymentsQr.dll file

you will get success message after it registered

Load Payment QR.tcp (Loading tcp)  in Tally ;;tdl file 

**Working**
1) After loading tcp file (Payment Qr.tcp) goto->Company Features(f11)

2) Goto->Accounting features

3) Set Enable Qr Code in Sales Invoice -> Yes

4) Select Payment Mode in which you want to receive amount

5) Set Include Amount-> Yes (Amount will be included in Qr Code)

6) Enter Information Based on Payment Mode (Make sure Details are valid)

7) After Done with Configuration Add/Open Sales Voucher

8) There will be a Button **Generate Qr Code** Click that to button to generate Qr Code for that Invoice

9) Before Going to Print Make Sure you generated Qr Code (By Clicking on Generate Qr Button)

10) Go and Print an Invoice Qr Code will be displayed 

11) Ask you Customer to Scan the Qr to Make the Payment

12) They Scan with any UPI Payment Apps


          For Bug Report and fixes please raise an issue.


