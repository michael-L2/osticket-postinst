<p align="center">
<img src="https://osticket.com/wp-content/uploads/2021/03/osticket-supsys-new-1-e1616621912452.png" alt="osTicket logo" />
</p>

<h1 align="center">osTicket: Post-Installation Configuration & Preparation</h1>

This guide will detail the post-installation of osTicket for an example helpdesk setup.

---

## **Environments and Technologies Used**

- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop Protocol (RDP)**
- **Internet Information Services (IIS)**
- **osTicket**

---

## **Operating System Used**

- **Windows 10** (21H2)

---

## **Prerequisites**

Before starting, make sure you've completed an osTicket setup! Feel free to follow my [previous guide](https://github.com/michael-L2/osticket-prereqs).

---

## **Initial Setup**

### **1. Create A Role**
1. In osTicket, click on **Agents** in the admin panel, then **Roles**.
2. Select **Add New Role** and name your role as you see fit.
3. Then, select **Permissions** and check every box. This will be your "SysAdmin" role.
![Resource Group](https://github.com/michael-L2/osticket-postinst/blob/main/5OsTicketConfig/3Enabling.png?raw=true)

---

### **2. Create A Department**
1. Click on **Departments** in the Agents panel.
2. Select **Add New Role** and name your role as you see fit.
3. Inside of **Settings**, configure as shown below, and **Create Dept**.
![Resource Group](https://github.com/michael-L2/osticket-postinst/blob/main/5OsTicketConfig/6Create.png?raw=true)

---

### **3. Create Some Teams**
1. Click on **Teams** in the Agents panel.
2. Select **Add New Team** and name your team accordingly, then **Create Team**.
3. Create a second team titled similarly to **Support**, or as you see fit.
![Resource Group](https://github.com/michael-L2/osticket-postinst/blob/main/5OsTicketConfig/8CreateTeam.png?raw=true)

---

### **4. Create Some Agents**
1. Click on **Agents** in the Agents panel.
2. Select **Add New Agent** and name your agent realistically, and include a fake email.
3. In **Access**, give this agent access to your previously created department, and give them the role you made prior.
4. In **Teams**, give them access to your team you've created earlier, click **Add**, then **Create Agent**.
![Resource Group](https://github.com/michael-L2/osticket-postinst/blob/main/5OsTicketConfig/10ConfAgent.png?raw=true)

5. Click on **Agents** in the Agents panel.
6. Select **Add New Agent** and name your second agent realistically, and include a fake email.
7. In **Access**, give this agent access to the default **Support** department, and give them full access.
8. In **Teams**, give them access to your **second team** you've created earlier, click add, then **Create Agent**.
![Resource Group](https://github.com/michael-L2/osticket-postinst/blob/main/5OsTicketConfig/13SecondAgent.png?raw=true)

---

### **5. Adding A User**
1. Click on **Agent Panel** on the top right, switching over to the Agent Panel.
2. Select **Users**, then click **Add User**.
3. Inside of **Lookup or create a user**, add a fake email and name, then **Add User**.
![Resource Group](https://github.com/michael-L2/osticket-postinst/blob/main/5OsTicketConfig/19AddedUser.png?raw=true)

---

### **6. Adding an SLA Plan**
1. Click on **Admin Panel** on the top right, switching over to the Admin Panel.
2. Select **Manage**, then click **Add New SLA Plan**.
3. Inside of **Add New SLA Plan**, set the name, schedule, and grace period in accordance to severity, then **Add Plan**.
4. Create **two more SLA Plans** with **varying levels** of intensity/severity.
![Resource Group](https://github.com/michael-L2/osticket-postinst/blob/main/5OsTicketConfig/22AddedSLA.png?raw=true)

---

### **7. Add Help Topics**
1. Click on **Help Topics** in the same **Manage** panel.
2. Select **Add New Help Topic**.
3. Inside of **Add New Help Topic**, make the topic realistic, and set the parent topic accordingly, then **Add Topic**.
4. Aim to create at least **five different topics**.
![Resource Group](https://github.com/michael-L2/osticket-postinst/blob/main/5OsTicketConfig/31AdditionalTopics.png?raw=true)

---

### **Congratulations!**
Your osTicket system is ready for some basic use! 🎉
