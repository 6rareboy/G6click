# G6click Changelog

**G6click V4.5**
4/30/24 <3

*New Features/Things*
- Added my own OOshutup10 config.
- Added Disable Microsoft Copilot.
- Added Xbox Gaming Service Remover.
- Added Corsair Icue Remover.
- Added Msi Dragon Center Remover.
- Added VisiSonics Remover.
- Added AMD Bloat Remover.
- Added Realtek Audio Remover.
- Added Gigabyte Bloat Remover.
- Added Orca Lite Installer.
- Added Nsudo Installer that opens automatically & displays instructions.
- Added Disable Nvidia HD Audio Device Sleep Timer Tweak to GPU Tweaks.
- Added Timer Res & Islc Installer, Making Timer Res Auto Start & Configure Itself for Win 10 or 11.
- Added Khorive's Ndis/Interrupt Moderation Tweaks.
- Added Device Manager Tweaks that disable unnecessary devices.

*Fixed*
- Fixed OOshutup10 Import Script.
- Fixed App Installer Links.
- Fixed HDCP Disabler in GPU Tweaks.
- Fixed Win32PrioritySeparation.
- Fixed Power Plan Links.
- Fixed Restore Point Code.
- Fixed Ghub Deleter.

*Removed*
- Removed HomeGroup Auto Detection Scripted & Replaced with a simpler approach.
- Removed The V4.1 Timer Res Installer/Section.

---

**G6click V5.0**
5/6/24 <3

*Added*
- Google Chrome installer.
- 7zip installer.
- Added more Intel services to debloat.
- Added more AMD services to debloat.
- New OOshutup10 Config.
- Priority Separation Section.
- NvidiaProfileInspector Import.

*Removers*
- Remote Desktop Connection Remover.
- Widget and WidgetService Remover.
- 15 More Apps Added to App Remover.

*Windows*
- Disable Transparency Effects.
- Turning On Darkmode.
- Gamemode Disabler.
- Hardware Accelerated GPU Scheduling Enabler.

*Device Manager*
- Microsoft Device Association Root Enumerator Disabler.
- Microsoft Hyper-V Virtualization Infrastructure Driver Disabler.

*Power Plan*
- Auto Activate Power Plan.
- Disable C States.
- Disable Core Parking.
- Disable Throttle States.

*Fixed*
- Setting Display For Performance Section.
- RtkAudioUniversalService Disable/Delete.
- App Removers not only stop services but disable them now.
- Nvidia Tweaks, Errors and Removed Nul Commands.
- Start Apps disabler now deletes StartUp Folder & StartUp Reg, then adds them back.
- Nul'd All App Removers.

*Updated*
- Updated OrcaLite to V2, Now Deletes Leftover Onedrive and UpdateOrchestrator tasks.

---

**G6click V5.2**
5/7/24 <3

*Big Improvement*
- V5.2 Adds back & fixes an invoke script originally removed, leading to -10 Processes.

*Small*
- Fixed Edge delete, it now also deletes the edge shortcuts.
- Suppressed/Nul'd Annoying things.

*Update*
- Updated Orca.
- Updated OrcaLite.
- Updated the pack to include both of them.

---

**G6click V5.3 Changelog!**
5/8/24 <3

*Added*
- Smart Screen Remover.
- LockApp Remover.
- UAC Disabler.
- IPv6 Disabler.

*Fixed*
- Restore Point Name.

---

**G6click V5.4 Changelog!**
5/14/24 <3

- Fixed Spelling Error.

---

**G6click V5.7 Changelog!**
5/20/24 <3

*New/Added*
- Enable Show Hidden Files and Folders.
- Disable Taskbar Widgets.
- Disable Stickykeys.
- New And More Nvidia Tweaks & Better Organization.
- Added Microsoft Visual Runtime Installer (Needed for SetTimerResolution.exe).
- DNS Jumper Installer.
- Nvidia Telemetry Uninstaller (Breaks Shadowplay/Clipping, Use OBS instead but it's optional).
- Made Device Manager Tweaks optional, and warned of potential issues.

*Revamps*
- Revamped the restore point section.
- Revamped the order of CTT Tweaks & Spelling for CTT Tweaks.
- Revamped Enable Darkmode and Gave the option for light mode.
- Revamped a majority of the GPU tweaks section!

*Fixed*
- OOshutup10 & Config now downloads in your %temp% folder.
- Fixed NDIS Tweaks displaying errors.
- Fixed NDIS tweaks closing if "Unable to detect".
- Fixed Remote Desktop Connection Remover.
- Fixed Wifi Fixer auto restarting.
- Fixed Device Manager Tweaks showing Intel errors for AMD users by nuling them.
- Removed ColorPrevalence.

---

**G6click V5.9 Changelog!**
5/20/24 <3

G6click V5.7 = 171KB & 3413 lines of code.
                 ^
G6click V5.9 = 186KB & 3665 lines of code.

*Created*
- New Network Tweaks V1 bat (Added in G6click).
- Search Remover (Not Optional but have an alternative).
- StartMenuExperienceHost Remover.
- ShellExperienceHost Remover.
- taskhostw Remover.
- Open Shell Menu Installer (Search alternative).
- New Nvidia tweak.

*Added*
- Red text for restore point to help others know it's recommended.

*Fixed*
- Spelling Errors.
- ASCII art positions.
- GPU Selection goto commands.

*Notes*
- Reduces processes by 4-6 (taskhostw.exe, ShellExperienceHost.exe, StartMenuExperienceHost.exe & UdkUserSvc_403e).

---

**G6click V6.0 Changelog!**
5/22/24 <3

G6click V5.9 = 186KB & 3665 lines of code.
                 ^
G6click V6.0 = 192KB & 3753 lines of code.

*Made*
- Made Process Destroyer, a batch file that disables over 30 different services using NSudo with the highest possible privileges.

*General*
- Moved Cleanup and Defrag Script to the very end of the script.

*DNS Section*
- Nul'd Google & Cloudflare DNS Change.
- Fixed the position of the ASCII art to be centered.
- Fixed spelling and spacing!

*Network Tweaks*
- Changed warning text to "Can cause connection issues, so be cautious. (Wouldn't Recommend)".
- Removed VLAN ID tweak, as it caused WiFi connection issues.
- Fixed spelling.

*Defrag*
- Took out unnecessary text.
- Added red text saying "Reminder, Might Take a while".
- Fixed the script automatically skipping.
- Moved the ASCII art border to the left slightly.

*Power Plan*
- Moved delete commands for default power plans to the end.
- Moved ASCII art border to the left slightly.
- Added red text: "1. (Recommended) Quaked Ultimate Performance".

*Orca Lite*
- Added an ASCII art border to explain Orca.
- Changed the ASCII art name to Orca Lite.
- Added Red text above choices saying "(Recommended)".

*App Debloat*
- Fixed Microsoft Teams remover.
- Added Red text saying "Reminder, will take a while".

---

**G6click V6.1 Changelog!**
5/24/24 <3

*Fixed*
- Fixed G6click extracting with 2 folders.
- Edited the "Read Me Important" txt file.
- Changed the Requirements for Process Destroyer installation.
- Fixed Nvidia Telemetry Client not skipping.
- Updated Process Destroyer to V1.5.

---

**G6click V6.2 Changelog!**
6/1/24 <3

G6click V6.1 = 193KB & 3753 lines of code.
                 ^
G6click V6.2 = 194KB & 3778 lines of code.

*Open Shell Menu/Windows Search*
- Made Windows Search Remover Optional.
- Added more emphasis on installing Open Shell Menu!

*Process Destroyer*
- Added more emphasis on requirements for Process Destroyer.
- Fixed spelling errors in Process Destroyer.

*Fixed*
- Fixed G6click version displaying as outdated.

*Unsupported Features*
- Updated info section.

---

**G6click V6.7 Changelog!**
6/19/24 <3

G6click V6.2 = 194KB & 3778 lines of code.
                 ^
G6click V6.7 = 202KB & 3839 lines of code.

*New Features*
- Administrator Privileges Detection: Prompts for elevation if not run as admin.
- Windows Defender Detection: Prompts to disable Windows Defender if running.
- TrustedInstaller Detection: Detects if disabled and reenables it for NSudo functionality.
- Auto install of G6click Tools folder (NSudo, Orca, AMD).
- Added AMD script to disable AMD-related bloat using NSudo.
- Orca now automatically executes in the Unnecessary Tasks Section.
- GPU Auto Detection with automatic GPU tweak application.
- Automatically applies 22 Dec/16 Hex Priority Separation.
- Visual C++ 2015-2022 Redistributable Detection & Auto-Installer.
- Auto Install Timer Res with Windows version detection and global application.
- Added Bluetooth Device (RFCOMM Protocol TDI) Disabler.
- Added Intel(R) Wireless Bluetooth (R) Disabler.
- Added Microsoft Bluetooth Enumerator Disabler.
- Added Microsoft Bluetooth LE Enumerator Disabler.
- Added Microsoft Print to PDF Disabler.
- Added Root Print Queue Disabler.
- Added Intel(R) Wi-Fi Disabler.
- Added WAN Miniport (IKEv2, IP, IPv6, L2TP, Network Monitor, PPPOE, PPTP, SSTP) Disablers.
- Added prompt to verify power plan import with automatic fallback to default schemes.
- Added Windows Cleanup section.
- Added Extras section.
- Added App Uninstaller to make non-Microsoft apps optional.
- App Installer now includes OBS Studio, Spotify, and Discord downloads.
- Updated Process Destroyer to V2.1 (disables LicenseManager, gpsvc, EventLog, PlugPlay & SgrmBroker; auto-executes via G6click).
- Added Service Disablers for Lms, Esifsvc, AppReadiness, DtsApo4Service, NVIDIA High Definition Audio, ArmouryCrateControlInterface, AsusAppService, ASUSOptimization, ASUSSoftwareManager, ASUSSwitch, ASUSSystemAnalysis, and ASUSSystemDiagnosis.

*Fixed*
- Group svchost.exe processes: Correctly detects RAM and applies proper `SvcHostSplitThresholdInKB` value.
- Optimized script speed (using timeout 1 instead of 2).
- Added error handling to menu choices to return to the selection prompt on invalid input.
- Nul'd all visual errors.

*Deleted*
- Removed System Theme section.
- Removed unnecessary `@echo off` lines.
- Removed `REM` and `timeout` commands in Device Manager Tweaks.