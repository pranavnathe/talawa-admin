[Admin Docs](/)

***

# Variable: MOCKS

> `const` **MOCKS**: (\{ `request`: \{ `query`: `DocumentNode`; `variables`: \{ `after`: `undefined`; `first`: `number`; `id`: `string`; `name`: `undefined`; `sortedBy`: \{ `id`: `string`; \}; `tagId`: `undefined`; `userId`: `undefined`; `where`: \{ `firstName`: \{ `starts_with`: `string`; \}; `lastName`: \{ `starts_with`: `string`; \}; \}; \}; \}; `result`: \{ `data`: \{ `getAssignedUsers`: \{ `ancestorTags`: `any`[]; `name`: `string`; `usersAssignedTo`: \{ `edges`: `object`[]; `pageInfo`: \{ `endCursor`: `string`; `hasNextPage`: `boolean`; `hasPreviousPage`: `boolean`; `startCursor`: `string`; \}; `totalCount`: `number`; \}; \}; `removeUserTag`: `undefined`; `unassignUserTag`: `undefined`; `updateUserTag`: `undefined`; \}; \}; \} \| \{ `request`: \{ `query`: `DocumentNode`; `variables`: \{ `after`: `string`; `first`: `number`; `id`: `string`; `name`: `undefined`; `sortedBy`: \{ `id`: `string`; \}; `tagId`: `undefined`; `userId`: `undefined`; `where`: \{ `firstName`: \{ `starts_with`: `string`; \}; `lastName`: \{ `starts_with`: `string`; \}; \}; \}; \}; `result`: \{ `data`: \{ `getAssignedUsers`: \{ `ancestorTags`: `any`[]; `name`: `string`; `usersAssignedTo`: \{ `edges`: `object`[]; `pageInfo`: \{ `endCursor`: `string`; `hasNextPage`: `boolean`; `hasPreviousPage`: `boolean`; `startCursor`: `string`; \}; `totalCount`: `number`; \}; \}; `removeUserTag`: `undefined`; `unassignUserTag`: `undefined`; `updateUserTag`: `undefined`; \}; \}; \} \| \{ `request`: \{ `query`: `DocumentNode`; `variables`: \{ `after`: `undefined`; `first`: `undefined`; `id`: `undefined`; `name`: `undefined`; `sortedBy`: `undefined`; `tagId`: `string`; `userId`: `string`; `where`: `undefined`; \}; \}; `result`: \{ `data`: \{ `getAssignedUsers`: `undefined`; `removeUserTag`: `undefined`; `unassignUserTag`: \{ `_id`: `string`; \}; `updateUserTag`: `undefined`; \}; \}; \} \| \{ `request`: \{ `query`: `DocumentNode`; `variables`: \{ `after`: `undefined`; `first`: `undefined`; `id`: `undefined`; `name`: `string`; `sortedBy`: `undefined`; `tagId`: `string`; `userId`: `undefined`; `where`: `undefined`; \}; \}; `result`: \{ `data`: \{ `getAssignedUsers`: `undefined`; `removeUserTag`: `undefined`; `unassignUserTag`: `undefined`; `updateUserTag`: \{ `_id`: `string`; \}; \}; \}; \} \| \{ `request`: \{ `query`: `DocumentNode`; `variables`: \{ `after`: `undefined`; `first`: `undefined`; `id`: `string`; `name`: `undefined`; `sortedBy`: `undefined`; `tagId`: `undefined`; `userId`: `undefined`; `where`: `undefined`; \}; \}; `result`: \{ `data`: \{ `getAssignedUsers`: `undefined`; `removeUserTag`: \{ `_id`: `string`; \}; `unassignUserTag`: `undefined`; `updateUserTag`: `undefined`; \}; \}; \})[]

Defined in: [src/screens/ManageTag/ManageTagMocks.ts:9](https://github.com/gautam-divyanshu/talawa-admin/blob/69cd9f147d3701d1db7821366b2c564d1fb49f77/src/screens/ManageTag/ManageTagMocks.ts#L9)