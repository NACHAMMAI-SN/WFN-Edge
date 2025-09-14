
# WFN-Edge

WFN is an enhanced Windows desktop application that builds upon the original Windows Firewall Notifier.  
=======
# WFN

WFN is an enhanced Windows desktop application that builds upon the original Windows Firewall Notifier.  

It provides real-time monitoring of network activity and simplifies firewall rule management with a clean WPF interface.

---

##  Features
-  Live monitoring of all TCP/UDP connections by process
-  Bandwidth graph and per-connection statistics
-  Map view to visualize remote endpoints
-  One-click firewall rule creation and management
-  Security log for reviewing past events
-  Modern WPF (XAML) interface

---

##  Built With
- **C#** (.NET Framework 4.8)
- **WPF (Windows Presentation Foundation)**
- **MSBuild / Visual Studio / .NET SDK**

---

##  Getting Started

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/WFN-PlusPlus.git
````

2. Build the project

   ```bash
   dotnet build WindowsFirewallNotifier.sln
   ```

3. Run the application

   ```bash
   dotnet run --project .\Console\Console.csproj
   ```

   Or launch the generated `.exe` from:

   ```
   Console\bin\Debug\net48\
   ```

---

##  Notes

1 Works on Windows only
2 Requires Windows Firewall enabled to function properly

---


