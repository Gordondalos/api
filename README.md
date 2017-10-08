s doctrine:generate:entities KitchenBundle

s doctrine:schema:update --force

s doctrine:generate:crud --overwrite --entity=KitchenBundle:Recipe --format=yml --with-write 


