
 | ----                    |                                |        |                     |
 | ----------------------- | ------------------------------ | ------ | ------------------- |
 | **Endpoint name**       | **Endpoint address**           |        |                     |
 | GetWorldsOfCreator      | /users/{userId}/worlds_creator | GET    |                     |
 | CreateWorld             | /worlds                        | POST   |                     |
 | UpdateWorld             | /worlds/{worldId}              | PATCH  |                     |
 | UpdateWorldImage        | /worlds/{worldId}/images       | POST   |                     |
 | xx                      |                                |        |                     |
 | GetAvailableWorldTags   | /worlds/tags                   | GET    |                     |
 | CreateAvailableWorldTag | /worlds/tags                   | POST   | tag                 |
 | UpdateAvailableWorldTag | /worlds/tags/{tagId}           | PATCH  | newTag              |
 | DeleteAvailableWorldTag | /worlds/tags/{tagId}                   | DELETE |                     |
 | xxx                     | xx                             | xx     |                     |
 | AddWorldTag             | /worlds/{worldId}/tags         | POST   | tagId               |
 | RemoveWorldTag          | /worlds/{worldId}/tags         | DELETE | tagId               |
 | xxxxxx                  | xx                             | xx     |                     |
 | CreateWorldAdmin | /worlds/{worldId}/admin        | POST   | motivationalLetter  |
 | UpdateWorldAdmin | /worlds/{worldId}/admin        | PATCH  | userId, approved    |
 | DeleteWorldAdmin        | /worlds/{worldId}/admin        | DELETE | userId              |
 | xxxx  x                 | xx                             | xx     |                     |
 | GetWorldActivity        | /worlds/{worldId}/activity     | GET    | dateFrom (optional) |
 | GetWorldsActivity       | /worlds/activity               | GET    |                     |
 | GetWorlds               | /worlds                        | GET    |                     |
