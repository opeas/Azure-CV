# Azure-CV
Moje CV hostowane w Azure Blob Storage wykorzystując Azure Functions oraz Azure CosmosDB pod adresem https://azurecvstorage.z20.web.core.windows.net/

## Pierwszy etap
- Folder frontend zawiera sama witryne, zostala ona stworzona poprzez edycje html jednego z CV na stronie https://styleshout.com/free-templates/ceevee/
- main.js zawiera kod licznika odwiedzajacych strone.

## Drugi etap
- Folder backend zawiera API.
- Stworzono Azure CosmosDB w portalu Azure.
- Stworzono Azure Function lokalnie poprzez CLI.
- Przekazano lokalną Azure Function do portalu Azure poprzez rozszerzenie VSC: Azure Functions.

## Trzeci etap
- Przekazano folder frontend do Azure Blob Storage poprzez rozszerzenie VSC: Azure Storage.
- Zaktualizowano ustawienia CORS w Azure Function, wpisano URL Azure Blob Storage.

## TO DO
- Zarejestrowanie domeny
- Stworzenie Azure CDN dla Azure Blob Storage, dodanie domeny do CDN
- Azure Function, która automatycznie zwiększa liczbę przepracowanych miesięcy w obecnej firmie
