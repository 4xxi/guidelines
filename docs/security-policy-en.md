# Security Policy

The requirements below must be applied to every project we do.

## The Passwords

* All password must have 14 symbols, min 1 number, min 1 special char.
* All passwords must be unique and should be used only once per one case.
* Nothing important can be written on the notebooks or paper or unencrypted files.
* Use password rotation for critical services annually. Update list of critical services annually. Specific projects might have extra such services.

## Accounts
* Use 2FA everywhere where it is available. ([Instruction in Phabricator for 4xxi members](https://phabricator.4xxi.com/w/administration/instructions/2fa/)).
* Do not use work accounts on non-work devices. If for some reason work account is used do not forget to log out and change the password immediately after that.

## The devices and wearables

* All working devices must be locked by default with the password or biometrics.
* All employees must use non-admin users on the computers. Some employees might use a user with admin privileges (by CTO approval) but every important action must require admin password.
* All devices used for work must be encrypted.
* All devices must have auto-block option less than 5 minutes.
* If an employee leaves the work place the computer and all devices must be locked.
* All notifications must be hidden in the locked state.
* All security updates must be applied as soon as possible but no later than a week.

## Transfer information

* Never transfer any information, code, configuration, access, passwords via public services or in an open (unencrypted) way.
* Use always [CaesarApp](http://secure.caesar.team) for sending private information.
* Use AWS S3 for storing any screenshot [instruction for employees](https://phabricator.4xxi.com/w/administration/instructions/amazon/).

## The Development

* Follow [OWASP recommendations](https://www.owasp.org/images/0/08/OWASP_SCP_Quick_Reference_Guide_v2.pdf).

## BYOD

* For employees' own device the same rules are applied.
* Chief Security Officer must be informed prior using any non-work device.
* Chief Security Officer must be immediately informed about any devices' losses.

## The Incidents

* Notify immediately Chief Security Officer about any devices' losses.
* Notify immediately Chief Security Officer about any violation of any rules above or even about any concerns that there is a violation by the company's representative. 
* If Chief Security Officer is not available, report Chief Technology Officer or Chief Executive Officer.
