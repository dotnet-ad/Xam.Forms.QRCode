# QRCode *for Xamarin.Forms*

[![NuGet](https://img.shields.io/nuget/v/Xam.Forms.QRCode.svg?label=NuGet)](https://www.nuget.org/packages/Xam.Forms.QRCode/) [![Donate](https://img.shields.io/badge/donate-paypal-yellow.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=ZJZKXPPGBKKAY&lc=US&item_name=GitHub&item_number=0000001&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted)

A QRCode Xamarin.Forms view based on SkiaSharp.

I ended up with a custom QRCode renderer because I wasn't satisfied with ZXing based solutions which:

* need to include the scanning parts even if you only need to render codes.
* rendering tweaking wasn't easy

## Install

Available on [NuGet](https://www.nuget.org/packages/Xam.Forms.QRCode/).

## Quickstart

```csharp
<?xml version="1.0" encoding="utf-8"?>
<ContentPage 
    ...
    xmlns:qr="clr-namespace:Xam.Forms;assembly=Xam.Forms.QRCode">

    <qr:QRCode 
            Content="https://github.com/mono/SkiaSharp"
            Color="Maroon" 
            Level="H" 
            WidthRequest="400" 
            HeightRequest="400" 
            VerticalOptions="Center" 
            HorizontalOptions="Center" />
    
</ContentPage>
```

## Thanks

* [codebude/QRCoder](https://github.com/codebude/QRCoder) : all QRCode generation algorithms

## Contributions

Contributions are welcome! If you find a bug please report it and if you want a feature please report it.

If you want to contribute code please file an issue and create a branch off of the current dev branch and file a pull request.

## License

MIT © [Aloïs Deniel](http://aloisdeniel.github.io)


