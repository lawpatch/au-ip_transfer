# Intellectual Property Transfer (Australia)

### Purpose

The language transfers ownership of intellectual property in **Australian** legal agreements.  You can't use it in deeds because it transfers future intellectual property. To transfer something that does not yet exist, there needs to be [some quid pro quo or consideration for the assignment.](https://jade.barnet.com.au/Jade.html#!article=65687)

The example below assumes the use of the LawPatch description clause <a href="https://github.com/lawpatch/lawpatch-docs" target="_blank">here</a>.

### Simple IP Transfers with LawPatch

Ownership of intellectual property is a technical area.  If you want to draft a transfer, you end up with a lot of formulaic language.  LawPatch allows you to factor the technical language out.  Here's an example of a transfer using the language in this repo:

> Provider <a href="" target="_blank">transfers ownership of intellectual property rights</a> in the Code to Customer.

Simple.

### Parameters

The language in this repo is *not* language that you can import wholesale with a simple incorporation by reference - it assumes that you have included certain information in the clause that imports it.

The intellectual property transfer parameters are:

- `Assignor` - The party transferring ownership of the intellectual property;
- `Assignee` - The party receiving ownership of the intellectual property;
- `Subject` - The entity containing the intellectual property rights that are to be transferred (the more specific you are in the description the better);
- `Territory` (optional) - The country or countries where the assignment applies; and
- `Exception` (optional) - An exception to the transfer of ownership.
 
### Territorial Restrictions
You will see that 'Territorial Restriction' is an optional parameter above. You can transfer intellectual property rights for use in one country without transferring them in other countries. For example, if you want to keep uisng your IP for your business in Germany and France, but you want to transfer the right to use it in Australia permanently to another business, you could transfer the IP to that business but limit the assignment to Australia. The person you transfer to could then, in Australia, use the intellectural property. But in other countries, they cannot. You continue to own the intellectual property in those other countries.  

If you do not specify a territorial restriction, then the transfer applies globally.

### Not Legal Advice

This is not legal advice.  Lawyers are involved in producing these terms, but they obviously aren't familiar with your circumstances.  Speak to your lawyer to make sure that the language is well aligned with your circumstances.

### Licence

The intellectual property transfer language is released under the license in `license.md`.
