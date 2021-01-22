# cas-test-applications
Test applications you can use to log into your CAS instance.

Deploy the .war files to a servlet container and then edit the web.xml in each:

  Change the <context-pararm> "cas-hostname" to the value for your CAS app server.

  In the CAS Authentication Filter and CAS Validation Filter:
    Change the "casServerLoginUrl" <init-param> to the CAS login URL for your CAS app server.
    Change the "service" <init-parm> to the service entry point you will use for this test application.
  
As their names indicate, these .war files use the CAS2 and SAML 1.1 protocols.
