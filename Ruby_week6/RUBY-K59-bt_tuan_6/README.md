# README

Cau 1. Phan biet new va create

	- new: new method only creates an object in memory, we haven’t touched the database.
		   In order to save the User object to the database, we need to call the save method


	- create: create method Combine two new methods and save to a create method

Cau 2. So sanh update_attribute vs update_attributes

	- update_attribute: if we update only a single attribute, using the singular update_attribute bypasses this restriction by skipping the validations

	- update_attributes: The update_attributes method accepts a hash of attributes, and on success performs both the update and the save in one step (returning true to indicate that the save went through). Note that if any of the validations fail, such as when a password is required to save a record, the call to update_attributes will fail
