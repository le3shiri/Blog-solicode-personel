## User Management – Services Overview

- **UserService**  
  _Purpose:_ CRUD operations & status toggling for user accounts  
  _Main Functions:_

  - `listUsers()`  
  - `createUser(data)`  
  - `updateUser(id, data)`  
  - `toggleStatus(id)`  
  - `deleteUser(id)`  

- **RoleService**  
  _Purpose:_ Assign or revoke roles for a given user  
  _Main Functions:_

  - `listRoles()`  
  - `assignRole(userId, role)`  
  - `removeRole(userId, role)`  

- **ModalService**  
  _Purpose:_ Handle the different modal dialogs in the UI (add, edit, assign-role, status, delete)  
  _Main Functions:_

  - `openAddUserModal()`  
  - `openEditUserModal(user)`  
  - `openAssignRoleModal(user)`  
  - `openStatusModal(user, action)`  
  - `openDeleteModal(user)`
