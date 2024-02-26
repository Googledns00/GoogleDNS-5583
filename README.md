![images](https://github.com/Googledns00/GoogleDNS-5583/assets/161330044/c80608db-b2ec-43ed-a83e-9d3da2e296c2)
// ExStart:SetMeteredLicense
// Set up metered public and private keys.
new Aspose.TeX.Metered().SetMeteredKey(
    "<type public key here>",
    "<type private key here>");
// ExEnd:SetMeteredLicense
// ExStart: VerifyMeteredLicense
#tab
if (Aspose.TeX.Metered.IsMetered())
{
    Console.WriteLine("Metered license is set successfully!");
}
else
{
    Console.WriteLine("Metered license is not set!");
}
// example: VerifyMeteredLicense
