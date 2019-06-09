Quick start
===========

* Once `downloaded <http://ecka.imbick.com/download>`_, extract Ecka to a folder on your computer.
* Open the `appsettings.json` file in the root of the Ecka folder and change the `installPath` setting of the `Ecka.StarCitizen.Plugin` plugin section to match the location of where Star Citizen is installed on your machine. The default is `c:\\program files\\roberts space industries\\starcitizen\\live\\bin64\\`
* Run `ecka.launcher.windows.exe`.
* Once it's running it will open the Ecka welcome screen in your browser.
* If you have only one connected network adapter or LAN IP address;
   * The welcome page will show you the IP address that you can use to connect your secondary device.
   * Either type this address in full into your second device's browser or scan the QR code to quickly open the correct address on your device.
* If you have more than one connected network or adapter or multiple LAN IP addresses you must choose which one your second device will be connecting over;
   * Choose the network adapter from the first list if more than one is available.
   * Then choose the IP address from the second list if more than one is available.
   * Then either type the displayed address in full into your second device's browser or scan the QR code to quickly open the correct address on your device.
* If no connected network adapter or LAN IP address is found you will only be able to connect to Ecka on the device it is running on;
   * Click the displayed link to open the page in your local browser.
* Once you see the Star Citizen flight screen on your second device you are ready to launch Star Citizen.
* Whilst Star Citizen is loading copy the `ecka.xml` control profile from the `\\Plugins\\Ecka.StarCitizen.Plugin.0.0.1\\` folder into your Star Citizen control profile folder at `[installPath]\\StarCitizen\\LIVE\\user\\Controls\\Mappings\\`.
* Once Star Citizen is up and running the last thing to do is apply the control profile by typing the command `pp_RebindKeys ecka` into the console.
   * You can access the console by pressing the tilde key "`~`" which is usually on the top left of the keyboard next to the number 1 key on the top row.
* Now Star Citizen is configured to respond to the commands sent from Ecka.


.. Once :doc:`installed </user-guide/installing>`, you can launch Ecka from the ``ecka.exe`` in the extracted folder. This will start Ecka and place an icon in the notification area.

.. When running you can right-click the icon to access the context menu. From here you can select commands that will interact with Ecka.

.. Stopping Ecka
.. =============
.. If you want to close the Ecka application you can choose ``Close`` from the context menu. This will instruct Ecka to begin closing down.
.. You can also close Ecka by using the :doc:`stop operation </api/service/GET-stop>` via the API.