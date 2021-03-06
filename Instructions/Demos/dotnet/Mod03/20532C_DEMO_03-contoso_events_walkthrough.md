# Module 3: Hosting Web Applications on the Azure Platform

# Demo: Contoso Events Walkthrough

1.  On the Start screen, click the **Desktop** tile.

1.  On the taskbar, click the **File Explorer** icon.

1.  In the Libraries window, go to Allfiles **(F):\\Mod03\\Democode\\Contoso.Events**, and then double-click **Contoso.Events.sln**.

1.  In the **Solution Explorer** pane, expand **Shared**.

1.  In the **Solution Explorer** pane, expand the **Contoso.Events.Data.Generation** project.

1.  On the Start screen, type **Azure Storage Emulator**.

1.  Click the **Windows Azure Storage Emulator – v3.4** tile.

1.  Switch back to the **Contoso.Events – Microsoft Visual Studio** window.

1.  In the **Solution Explorer** pane, right-click the **Contoso.Events.Data.Generation** project, point to **Debug**, and then click **Start New Instance**.

1. Wait for the console application to close and also for debugging to stop.

1. Close the Contoso.Events – Microsoft Visual Studio application.

1. On the Start Screen, right-click the **Visual Studio 2013** tile, and then click **Run as Administrator**.

1. On the **File** menu, point to **Open**, and then click **Project/Solution**.

1. In the **Open Project** dialog box, perform the following steps:

	a.  Go to **Allfiles (F):\\Mod03\\Democode\\Contoso.Events**.

	b.  Click the **Contoso.Events** solution file.

	c.  Click **Open**.

1.  In the **Solution Explorer** pane, right-click the **Contoso.Events** solution, and then click **Properties**.

1.  In the **Solution ‘Contoso.Events’** **Property Pages** dialog box, perform the following steps:

	a.  Make sure that **CommonProperties** =&gt; **Startup Project** is selected in the navigation menu on the left side of the screen.

	b.  Click **Multiple startup projects**.

	c.  For **Contoso.Events.Cloud**, set the **Action** to **Start**.

	d.  For **Contoso.Events.Management**, set the **Action** to **Start without debugging**.

	e.  Ensure that for all the remaining projects, the **Action** is set to **None**.

	f.  To close the dialog box, click **OK**.

1.  On the **Debug** menu, click **Start Debugging**.

	> If Visual Studio prompts you to restart the Azure emulator in an elevated context, click **OK**.

1.  In the notification area, locate and right-click the **IIS Express** icon.

1.  Point to **Contoso.Events.Management** under the **View Sites** header, and then click the URL under the **Browse Applications** header.

1.  In Internet Explorer, locate and click the **Home – Contoso Events** tab.

1.  Click any one of the sales conference events to go to the event details webpage.

	> If a sales conference is not listed in the Upcoming Events section, you can click **All Events** to see all the events.

1.  To go to the event’s registration page, click **Register Now**.

1.  In the **Region** box, type **Western**.

1.  In the **AnnualSales** box, provide the value **45000**.

1.  In the **FirstName** box, provide the value **Corrine**.

1.  In the **LastName** box, provide the value **Horn**.

1.  Click **Submit**.

1.  In Internet Explorer, locate and click the **Home – Contoso Events Administration** tab.

1.  Click **Go to Events List**.

1.  Locate the same sales conference that you registered for in the previous step.

1. In the grid, click **Sign-In Sheet** next to the event’s name.

1. Every 30 seconds (or less), refresh the page to see if the Sign-in Sheet is generated.

	> When the box changes from blue to yellow and a hyperlink with the text Sign-In Sheet displays, it indicates that the Sign-in Sheet is generated.

1.  Click the **Sign-In Sheet** hyperlink to download the Microsoft Word document.

1.  To view the file, click **Open** in the download dialog box.

1.  Close the **Internet Explorer** application.

1.  Close the **Contoso.Events – Microsoft Visual Studio** application.
