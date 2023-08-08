# PhillipNova

salesforce Credential

https://phillipnova--dev1.sandbox.my.salesforce.com/services/Soap/u/52.0
praveen@pnpl.com.dev
Pajtth3A9ayxxMrG6QzLtpgwf


DB View name

[vw_All_Leads]
[vw_LeadTrack_ApplicationInfo_TaskForce]
[vw_Report_Gl_Journal_Entry]
[vw_client_corporate_ContactDetails]
[vw_individual_ContactDetails]
[vw_DastFinancialSummary]
[vw_DastTradeConfirmationPNL_SF]

// class to check whther field have value or not
public class PNBUtil_isFieldBlank {

    /**
     * helloExample: not return value, only print "hello" + message.
     * 
     * 
     * {talendTypes} String
     * 
     * {Category} User Defined
     * 
     * {param} string("world") input: The string need to be printed.
     * 
     * {example} helloExemple("world") # hello world !.
     */
	
	public static Boolean isFieldBlank(String value) {
		if (value == null || value.equals("") || value.equals(" ") || value.isEmpty()|| value.equals("None") || value.length() == 0 || value.equals("null"))
		return true ;
		else
			return false;
		}
}

