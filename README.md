# Requirements

* *1. Functional Requirements*
	* *1.1. User Requirements*
		 * *1.1.1. Create User*
			 * *1.1.1.1.* Users shall enter unique username
			 * *1.1.1.2.* Users shall enter display name
			 * *1.1.1.3.* Users shall enter phone number
			 * *1.1.1.4.* Users shall enter unique e-mail
			 * *1.1.1.5.* Users shall select user role
				 * *1.1.1.5.1.* Guest
				 * *1.1.1.5.2.* Admin
				 * *1.1.1.5.3.* Super Admin
			 * *1.1.1.6.* Users shall choose either enabled or disabled user
		* *1.1.2.* Save User
			* *1.1.2.1.* Users shall be able to save to be created user credentials
		* *1.1.3.* List User
			* *1.1.3.1.* Users shall be able to see all created users
				* *1.1.3.1.1.* ID
				* *1.1.3.1.2.* User Name
				* *1.1.3.1.3.* Email
				* *1.1.3.1.4.* Enabled
			 * *1.1.3.2.* Users shall be able to sort list by
				* *1.1.3.2.1.* ID
				* *1.1.3.2.2.* User Name
				* *1.1.3.2.3.* Email
				* *1.1.3.2.4.* Enabled			 
			* *1.1.3.3.* Users shall be able to hide disabled users
	* *1.2. System Requirements*
		* *1.2.1* The system shall create unique ID for each created user
		* *1.2.2* The system shall check uniqueness of  email and username in the creation phase
