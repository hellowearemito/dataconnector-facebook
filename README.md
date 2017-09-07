# Facebook Data Connector
by Mito 

Our data connector for Google Data Studio provides access to Facebook campaign insights via the Marketing API. Data are accessed directly from Facebook API endpoints using the privileges the user is assigned in Facebook Business Manager.

### Usage
To be able to use this connector the user has to be assigned to a Facebook Business Manager account with access to Ad Campaigns. The user needs at least ‘ads_read’ scope privileges.
The data connector fetches API data through a Facebook Application called "Data Connector for Data Studio" that is pre-configured for the Marketing API. Upon first connection, the data connector Facebook app will ask for permission to acess your data. You need to grant read privilege on your ads for the app to be able to fetch data. 

### Terms of Use and Privacy Policy
This is data connector is under continous development and shall be used with care. Mito does not take any responsibility for using, mis-using or abusing this software either in development, testing, staging or production environments; nor for any negative effect may incur due to the malfunction of this software. 

### Support
Please feel free to submit your comments or bug reports as issues in this repository: https://github.com/hellowearemito/dataconnector-facebook/issues

### Imprint
This connector is developed by Mito, a digital agency located in Budapest, Hungary. To find out more, check out our website: https://mito.hu
