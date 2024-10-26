[Scrypted Documentation](../globals.md) / ScryptedUser

# Interface: ScryptedUser

ScryptedUser represents a user managed by Scrypted.
This interface can not be implemented, only extended by Mixins.

## Methods

### getScryptedUserAccessControl()

> **getScryptedUserAccessControl**(): `Promise`\<[`ScryptedUserAccessControl`](ScryptedUserAccessControl.md)\>

Retrieve the ScryptedUserAccessControl for a user. If no access control object is returned
the user has full access to all devices. This differs from an admin user that can also
access admin related system services.

#### Returns

`Promise`\<[`ScryptedUserAccessControl`](ScryptedUserAccessControl.md)\>
