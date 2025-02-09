## Automated Diagnostics
### Getting Started

::: tip Prerequisites
To use the Automated Diagnostics Solution, you must either have a **PagerDuty Runbook Automation** license or a **Process Automation** license.
See the [FAQ](/learning/solutions/automated-diagnostics/feedback-faq) for details on how to use with **Rundeck Community**.
If you do not have a license for either of these products, [contact us](https://www.pagerduty.com/contact-us/runbook-automation/) to learn more.

**You must be running version 4.3.0 or greater to use this Solution.**
:::

Follow the steps below to download and import the Automated Diagnostics Jobs and Tours:
#### Download the **Automated Diagnostics Solution package**.
1. Download the latest release of the Automated Diagnostics Solution [here](https://github.com/rundeckpro/automated-diagnostics-project/releases/download/1.1/automated-diagnostics-1.1.zip).<br><br>
2. Open the **.zip** file and there should be two files inside the folder:
   * **`automated-diagnostics-xxxxxxx.rdproject.jar`**
   * **`system-tours-xxxxxxxx.zip`**

#### Create a project in your Runbook Automation environment:
1. Click the **P** in the upper left corner to navigate to the Main Dashboard <br><br>
2. Click the blue **New Project+** button:
![Add Project](@assets/img/solutions-auto-diag-add-project.png)<br><br>
3. Copy the following into the **Project Name** field:  **`automated-diagnostics`**
![Name Project](@assets/img/solutions-auto-diag-name-project.png)<br><br>
4. Provide a Label for a more "user-friendly" name - such as _Automated Diagnostics_ <br><br>
5. Click the green **Create** button

#### Import the archive file into your new project:
1. In your new project, click the **gears** in the lower left corner for **Project Settings**<br><br>
2. Choose **Import Archive** from the menu:
![Import Archive](@assets/img/solutions-auto-diag-import-archive.png)<br><br>
3. For the **Choose a Rundeck archive**, select the **`automated-diagnostics-xxxxxx.jar`** from the downloaded resources.<br><br>
4. Leave all of the import settings as their defaults<br><br>
5. Click green **Import** button

#### Import the Tours:
1. Click the **gear-icon** in the upper right and select **Tour Manager**<br><br>
2. Click on **Import/Export** and select Import:
![Import Tours](@assets/img/solutions-auto-diag-import-tours.png)<br><br>
3. Select the **system-tours-xxxxx.zip** file from the downloaded resources<br><br>
4. Click on the green **Import** button
   ::: tip Note
   The Tours in the Automated Diagnostics Solution will help you integrate the product with various services (such as AWS) and other PagerDuty products.  
   If you are looking for a more general introduction to PagerDuty’s Automation products, it is recommended to review the contents of the [Welcome Project](/learning/howto/welcome-project-starter.html).
   :::

### **With the Jobs and Tours imported, you can now follow the [<span style="color:green"><ins>in-app Tours!</ins></span>](/learning/solutions/automated-diagnostics/tours.html)**
