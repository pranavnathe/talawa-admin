[Admin Docs](/)

***

# Variable: MOCKS

> `const` **MOCKS**: (\{ `request`: \{ `notifyOnNetworkStatusChange`: `boolean`; `query`: `DocumentNode`; `variables`: \{ `address`: `undefined`; `description`: `undefined`; `filter`: `string`; `first`: `number`; `image`: `undefined`; `name`: `undefined`; `orderBy`: `string`; `skip`: `number`; `userId`: `undefined`; `userRegistrationRequired`: `undefined`; `visibleInSearch`: `undefined`; \}; \}; `result`: \{ `data`: \{ `createOrganization`: `undefined`; `createSampleOrganization`: `undefined`; `organizationsConnection`: [`InterfaceOrgConnectionInfoType`](../../../../utils/interfaces/interfaces/InterfaceOrgConnectionInfoType.md)[]; `user`: `undefined`; \}; \}; \} \| \{ `request`: \{ `notifyOnNetworkStatusChange`: `undefined`; `query`: `DocumentNode`; `variables`: \{ `address`: `undefined`; `description`: `undefined`; `filter`: `undefined`; `first`: `undefined`; `image`: `undefined`; `name`: `undefined`; `orderBy`: `undefined`; `skip`: `undefined`; `userId`: `string`; `userRegistrationRequired`: `undefined`; `visibleInSearch`: `undefined`; \}; \}; `result`: \{ `data`: \{ `createOrganization`: `undefined`; `createSampleOrganization`: `undefined`; `organizationsConnection`: `undefined`; `user`: [`InterfaceUserType`](../../../../utils/interfaces/interfaces/InterfaceUserType.md); \}; \}; \} \| \{ `request`: \{ `notifyOnNetworkStatusChange`: `undefined`; `query`: `DocumentNode`; `variables`: `undefined`; \}; `result`: \{ `data`: \{ `createOrganization`: `undefined`; `createSampleOrganization`: \{ `id`: `string`; `name`: `string`; \}; `organizationsConnection`: `undefined`; `user`: `undefined`; \}; \}; \} \| \{ `request`: \{ `notifyOnNetworkStatusChange`: `undefined`; `query`: `DocumentNode`; `variables`: \{ `address`: \{ `city`: `string`; `countryCode`: `string`; `dependentLocality`: `string`; `line1`: `string`; `line2`: `string`; `postalCode`: `string`; `sortingCode`: `string`; `state`: `string`; \}; `description`: `string`; `filter`: `undefined`; `first`: `undefined`; `image`: `string`; `name`: `string`; `orderBy`: `undefined`; `skip`: `undefined`; `userId`: `undefined`; `userRegistrationRequired`: `boolean`; `visibleInSearch`: `boolean`; \}; \}; `result`: \{ `data`: \{ `createOrganization`: \{ `_id`: `string`; \}; `createSampleOrganization`: `undefined`; `organizationsConnection`: `undefined`; `user`: `undefined`; \}; \}; \})[]

Defined in: [src/screens/OrgList/OrgListMocks.ts:94](https://github.com/gautam-divyanshu/talawa-admin/blob/69cd9f147d3701d1db7821366b2c564d1fb49f77/src/screens/OrgList/OrgListMocks.ts#L94)