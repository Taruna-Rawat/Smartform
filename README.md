# Smartform
Smart Form in SAP ABAP.
There are two parts of Smartform:
1. Driver Program: Go to tcode se38 to create a program to send data into smartform.
2. Design smartorm: Go to tcode smartforms to design smartform. Further steps are given as follows:

1. Draw windows in Form Painter as given below:
  ![Form Painter](https://github.com/Taruna-Rawat/Smartform/assets/117479444/405294b8-18b8-485e-8cbd-610c12fa0b76)

2. In Form Interface, mention input table name as follows:
  ![Form Interface](https://github.com/Taruna-Rawat/Smartform/assets/117479444/dbe2f08f-0368-4731-b7a6-1c44e4353955)

3. In Global Definitions, mention input table name as follows:
 ![Global Definitiosn](https://github.com/Taruna-Rawat/Smartform/assets/117479444/1ed2d3c2-ef16-422c-892a-e1d64301c4ba)

4. For heading, create a new window. Under that create a new template. A template disolays static data.
![Window 1](https://github.com/Taruna-Rawat/Smartform/assets/117479444/42af0218-94e5-4539-8940-6d1259e3142d)

5. For output table, create a new window. Under that create new table. A table displays dynamic data. Width of a table is lesser than width of the window. 
   By clicking on Grid symbols.
   ![Define Table](https://github.com/Taruna-Rawat/Smartform/assets/117479444/611f78c6-d3e2-4f99-ba5c-c9280a07d693)
  
6. Header Section contains headers of the table. Under Cell, create a new text. When 5 partitions are made. 5 new cells are created under Header and Main Area.
![Header](https://github.com/Taruna-Rawat/Smartform/assets/117479444/d9fee8bd-ccae-44b5-a615-9dc569551bfb)

7. Main Area Section contains data of the table to be displayed. Under Cell, create a new text.
![Main Area](https://github.com/Taruna-Rawat/Smartform/assets/117479444/1c8b62e0-dfb9-427e-a8b1-360438e647bd)

9. Go to tcode se38, then driver program 'Z_SF'.
![Input](https://github.com/Taruna-Rawat/Smartform/assets/117479444/bbc07422-81a3-4179-8e58-899e6790efeb)

10. execute the program. Enter Output device as LP01.
 ![Smartform](https://github.com/Taruna-Rawat/Smartform/assets/117479444/be07e2e8-cc3d-4284-9840-be2f0f7a203a)
