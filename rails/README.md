# Rails Generators


## models

    rails g model Language name:string:uniq short_code:string{'2'}:uniq

# Some samples of migrations

Easiest (and best) way to make a migration file, is with the generator

    rails g migration AddContraintToNameOfUsers

rails g migration add_index_to_column_name :column_name, :unique => true




    rails g migration AddColumnsToCompanies vat_number:string

