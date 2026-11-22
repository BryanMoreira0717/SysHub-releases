# Third-party notices

SysHub ships with the following components. Each is used under its own license; full license texts are available at the linked projects.
Components only used to build (code generators, SDK build tools) are not redistributed and are not listed.

| Component | Version | License | Project |
|---|---|---|---|
| .NET runtime | 10.0 | MIT | https://github.com/dotnet/runtime |
| Windows App SDK (WinUI 3, Foundation, InteractiveExperiences, DWrite) | 2.7.0 | Microsoft Software License Terms (redistributable) | https://github.com/microsoft/windowsappsdk |
| Microsoft.Web.WebView2 (dependency of WinUI) | 1.0.3719.77 | Microsoft Software License Terms | https://aka.ms/webview |
| LibreHardwareMonitorLib | 0.9.6 | MPL-2.0 | https://github.com/LibreHardwareMonitor/LibreHardwareMonitor |
| BlackSharp.Core | 1.0.7 | MPL-2.0 | https://github.com/Blacktempel/BlackSharp |
| DiskInfoToolkit | 1.1.2 | MPL-2.0 | https://github.com/Blacktempel/DiskInfoToolkit |
| RAMSPDToolkit-NDD | 1.4.2 | MPL-2.0 | https://github.com/Blacktempel/RAMSPDToolkit |
| HidSharp | 2.6.4 | Apache-2.0 | https://software.seekye.com/hidsharp |
| H.NotifyIcon / H.NotifyIcon.WinUI / H.GeneratedIcons.System.Drawing | 2.4.1 | MIT | https://github.com/HavenDV/H.NotifyIcon |
| CommunityToolkit.Mvvm / Common | 8.4.2 / 8.2.1 | MIT | https://github.com/CommunityToolkit/dotnet |
| CommunityToolkit.WinUI (SettingsControls, Converters, Extensions, Helpers, Triggers) | 8.2.251219 | MIT | https://github.com/CommunityToolkit/Windows |
| Microsoft.Data.Sqlite | 10.0.15 | MIT | https://github.com/dotnet/efcore |
| SQLitePCLRaw (bundle_e_sqlite3, core, provider, lib) | 2.1.13 | Apache-2.0 | https://github.com/ericsink/SQLitePCL.raw |
| SQLite | (bundled by SQLitePCLRaw) | Public domain | https://sqlite.org |
| Dapper | 2.1.100 | Apache-2.0 | https://github.com/DapperLib/Dapper |
| Serilog, Serilog.Extensions.Hosting/Logging, Serilog.Sinks.File | 4.4.0 / 10.0.0 / 7.0.0 | Apache-2.0 | https://github.com/serilog/serilog |
| Microsoft.Extensions.* (Hosting, DI, Logging, Options) | 10.0 | MIT | https://github.com/dotnet/runtime |
| System.Management | 10.0.15 | MIT | https://github.com/dotnet/runtime |
| Velopack (installer and updates) | 1.2.161 | MIT | https://github.com/velopack/velopack |

## MPL-2.0 components

LibreHardwareMonitorLib and the Blacktempel toolkits are used unmodified, as binary libraries. Their source code is available at the project links above, as required by the Mozilla Public License 2.0.

## Hardware access drivers

Some CPU and motherboard sensors are read through LibreHardwareMonitor's kernel driver (PawnIO), which SysHub does not ship. When the driver is missing, those readings show "—".
