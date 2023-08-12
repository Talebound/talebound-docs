
 |                    |                                                   |        |     |
 | ------------------ | ------------------------------------------------- | ------ | --- |
 | **Endpoint name**  | **Endpoint address**                              |        |     |
 | CreateMenu         | sql only                                          |        |     |
 | UpdateMenu         | /menus/{menuId}                                   | PATCH  |     |
 | DeleteMenu         | Sql only                                          |        |     |
 | GetMenu            | /menus/{menuId}                                   | GET    |     |
 | CreateMenuItem     | /menus/{menuId}/items                             | POST   |     |
 | UpdateMenuItem     | /menus/{menuId}/items/{menuItemId}                | PATCH  |     |
 | DeleteMenuItem     | /menus/{menuId}/items/{menuItemId}                             | DELETE |     |
 | GetMenuItems       | /menus/{menuId}/items                             | GET    |     |
 | ===========        |                                                   |        |     |
 | CreateMenuItemPost | /menus/{menuId}/items/{menuItemId}/posts          | POST   |     |
 | UpdateMenuItemPost | /menus/{menuId}/items/{menuItemId}/posts/{postId} | PATCH  |     |
 | DeleteMenuItemPost | /menus/{menuId}/items/{menuItemId}/posts/{postId} | DELETE |     |
 | GetMenuItemPosts   | /menus/{menuId}/items/{menuItemId}/posts          | GET    |     |
