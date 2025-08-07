Name: Header
Description: Stores information and assets associated with the site's header e.g. logo, search placeholder, mega menu

# Fields

1. Logo
   id: logo
   type: Asset
   required

2. Search placeholder
   id: searchPlaceholder
   type: symbol
   required
   validations: max character length 20

3. Account Link
   id: accountLink
   type: symbol
   required
   validations: should be a relative url, i.e. start with `/`. e.g. `/account`
