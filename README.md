This contains a csv file for each of the models we are wanting to populate within the Odoo environment, and the necessary fields to be bringing them in.

while creating the queries to directly pull this from Sage100Contractor, you will want to start with the files that have no dependencies on others, and work your way to the others where those dependencies exist. Using the following sequence should allow you to add IDs where necessary, and make importing the data easier.

Sequence:

contacts.csv
vendors.csv
uom.csv
products.csv
quotation_template.csv
vendor_suppliers.csv

departments.csv
employees.csv
vehicle_models.csv
fleet.csv

(pricelists are still a work in progress)
product_pricelist.csv
product_pricelist_items.csv

(inventory is a work in progress)