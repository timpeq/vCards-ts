vCards TS
=====
Create vCards to import contacts into Outlook, iOS, Mac OS, and Android devices from your website or application.

This is a port of [vCards JS](https://github.com/enesser/vCards-js) by Eric J Nesser, released under the MIT License.

Originally ported to TypeScript by Pawel Kaczynski <pawel@kaczynski.scot>

Modified by Tim Pequignot to support [Deno](https://deno.land/)

### Example:

```ts
import { vCard } from "https://deno.land/x/vcard@v1.0.7d/mod.ts";
const card = new vCard();
card.firstName = "Robert",
card.lastName = "Smith",
card.nickname = "Bob",
card.title = "Owner",
card.organization = "BobCo",
card.cellPhone = "+1 555-555-5555",
card.note = "Has 3 kids named Bob"

console.log(card.getFormattedString());
```
