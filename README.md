# Item Fulfillment Merger (2016)

![demo](/img/IF_Merge_diagram.png)

## Requirement

```bash
Required customers to sign multiple documents to acknowledge proof of delivery. It needed to group these fulfillments into a single document in order to improve the efficiency of the fulfillment process and reduce the risk of losing the confirmation slip.

1. Only item fulfillment records with similar shipping addresses can be merged.
2. The item fulfillment records that are grouped together into a single printed document need to be logged in NetSuite. (This can be done using a variety of methods, multi-select field, custom record, etc).
3. The user needs to be able to print the single printed document multiple times.
a. This requirement is intended to allow reprints in case the user loses the document.
4. The single printed document needs to be given its own unique identification number.
5. The single printed document needs to have all of the same features as the current packing slip form used by Norpak.
6. Each item from each fulfillment record needs to be listed with quantities from each customer sales order specified.
  a. e.g. 10 widgets from Sales Order 10X, 12 widgets from Sales Order 9B
7. User needs to be able to create a merged fulfillment document from (a) the fulfillment record as well as (b) a standalone application found on the main menu. With option a, the current record should be sourced as a parameter.

```

## Running Results

![plp_cell](/img/IF_Merge_1.jpg)

![plp_cell](/img/IF_Merge_2.jpg)

![plp_cell](/img/IF_Merge_3.png)
