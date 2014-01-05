2. Customer Protection Requirements
	- In order to protect customers which may not find a Provider's services suitable, all Service Providers *must* agree to an unconditional money back policy of at least 3 days. The Service Provider must issue a refund within 24 hours of the customer's refund request.
	- In order to protect customers, access to systems must strictly be controlled.
		* Private keys *are recommended* to be used when possible, such as over the SSH and SFTP protocols.
		* It is *recommended* that backend services, such as SSH or MySQL, not be on a public IP address.
	- To protect customer data, all hosts *must* employ redundancy in the case of a hardware failure. An example basic implementation of this would be a RAID 1 disk array, whereas a prefered implementation would be a RAID 1 with daily offsite backups. 
	- In order to ensure customer payment security, hosts *must* meet compliance with their payment processing partners.
		* To ensure legitimacy with the purchasing of products or services through the applicant through PayPal, we require that all business PayPal accounts be of "Verified" status, which must be displayed on your website.
		* Credit card information or other financial information *must not* be stored in an easily readable or reversible form.
	- In order to maintain clients' privacy while transmitting data to service providers, we require certain security protocols to be in place.
		* Hosts *must* enable SSL on their site, to allow client details to be transmitted encrypted. We recommend that service providers use EV SSL where possible.
		* SSL *must* be enforced in any areas of the site in which financial interactions take place, or customers' personal information is displayed. It is not permissible to allow display of any of these pages over a protocol other than SSL.
		* When service providers are accepting payment details directly on their site, they *must* meet PCI compliance, as required by local authorities.