Report ZKZ_TEST_GITHUB.

select * from mara
into table @data(lt_mara)
up to 10 rows.
If sy-subrc = 0.
Endif.
