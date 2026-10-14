# NopCommerce-Practise

> **Note:** this project was originally developed under my earlier GitHub account, [sajid43677/NopCommerce-Practise](https://github.com/sajid43677/NopCommerce-Practise), and was moved to this account in October 2026.

A practice copy of the [nopCommerce](https://www.nopcommerce.com/) open-source e-commerce platform (**version 4.70.3**), set up for learning plugin development.

## What's in this repo

- The full nopCommerce solution (`NopCommerce.sln`): `Libraries`, `Presentation` (`Nop.Web`, `Nop.Web.Framework`), `Plugins`, `Tests` and the `Build` scripts.
- The standard plugins that ship with nopCommerce (PayPal Commerce, UPS, Avalara tax, Google Analytics, Facebook Pixel, Brevo, Omnisend and others).
- Two extra plugins added for practice:
  - **NopStationGallary** (`Nop.Plugin.Misc.NopStationGallary`) is a small plugin that lists the nopStation team members.
  - **Web API Frontend** (`Nop.Plugin.Misc.WebApi.Frontend`) exposes nopCommerce data through a web API for a separate frontend.

## Tech stack

ASP.NET Core, C#, Entity Framework / linq2db data layer used by nopCommerce, SQL Server, Razor views.

## Run it

1. Open `NopCommerce.sln` in Visual Studio (a recent version with .NET 8 support).
2. Set `Nop.Web` as the startup project and run it.
3. On first launch the installation wizard asks for a database connection. Point it at a local SQL Server instance.

See `Deploying.Readme.txt` for deployment notes. For the platform itself, use the [official nopCommerce docs](https://docs.nopcommerce.com/).

## License

nopCommerce is distributed under its own license. See `LICENSE.md`.
