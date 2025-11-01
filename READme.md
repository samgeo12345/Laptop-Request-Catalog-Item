# Laptop Request Catalog Item

### Project Overview

The goal is to design and implement a **Laptop Request Catalog Item** in ServiceNow that allows employees to easily request laptops for official use.

---

### Project Details
- **Project Title:** Laptop Request Catalog Item
- **NM ID:** F8040B9B0F40D3F81374579A90F54118  
- **Platform:** ServiceNow  
- **Category:** ServiceNow System Administrator  
- **Level:** Intermediate  

---

### Modules Implemented
1. **Update Set**
   - Created to record all configuration changes.
2. **Service Catalog Item**
   - Added “Laptop Request” form with fields like:
     - Employee Name  
     - Department  
     - Laptop Type / Model  
     - Justification  
     - Manager Approval  
3. **UI Policy**
   - Set rules to show or hide fields dynamically based on user input.
4. **UI Action**
   - Added custom buttons like “Reset Form”.
5. **Export Update Set**
   - Exported as XML for migration to other instances.
6. **Login to Another Instance**
   - Imported the update set into another instance and validated the setup.
7. **Testing**
   - Verified all fields, form actions, and workflow behavior.
8. **Conclusion**
   - The catalog item works efficiently and supports dynamic form interaction.

---
