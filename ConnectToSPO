#Connect to SharePoint Online
$adminUPN = "user@domain.com"
$orgName = "domain"
$userCredential = Get-Credential -UserName $adminUPN -Message "Type the password."
Connect-SPOService -Url https://$orgName-admin.sharepoint.com -Credential $userCredential
Write-Host "You're already connect to O365 Tenant, Welcome!!" -ForegroundColor Green
