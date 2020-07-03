# QrCodeForPayments-Compiled
Generate QR Code in Sales Invoice for making payments



Requirements:

1) Microsoft.net framework version 4

2) .Net Framework 4.x.x

3) Download/Clone all the files (PaymentsQr.dl,QrCoder.dll,Payment QR.tcp)

You can Download from here : https://dotnet.microsoft.com/download/dotnet-framework/net40

Get Started and Registering DLL

Open CMD in administrator Mode (Elevated mode)

    For 64 Bit
Type cd C:\Windows\Microsoft.NET\Framework64\v4.0.30319 ;; change directory

    For 32 Bit
Type cd C:\Windows\Microsoft.NET\Framework\v4.0.30319 ;; change directory

Type regasm PaymentsQr.dll /codebase ;;Give Full path of the PaymentsQr.dll file

you will get success message after it registered

Load Payment QR.tcp (Loading tcp)  in Tally ;;tdl file 
