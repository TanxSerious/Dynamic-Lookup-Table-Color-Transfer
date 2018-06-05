# Dynamic-Lookup-Table-Color-Transfer
Directive Local Color Transfer Based on Dynamic Lookup Color Transfer
/********************************************************************************/
/*
Function : Directive Color Transfer Based on Dynamic Look-up Color Table
Author   : Zhenshan Tan
Last Time: 2018-05-28
*/
/********************************************************************************/
This program uses the DLL of opencv 2.4.9 and GDAL. 

(1)How to use the software?
① Choose the source and the reference and the result paths (push the buttons respectively).
② Double-click the "Weight List" to change the weights to construct the mapping relationship. 
   You can push the "Default" button to read the text of weights or to get the default values.
③ Push the "Color Transfer" button. 

(2)How to set the weights?
The program has ordered the clustering colors based on the persentage and the centroid. 
So we do not have to set the weights of the persentage and the centroid again, we keeps them the default values.
Just change the weight of the Directive. The program has been simplified. 
We only need to change the directive weights of the source image.

The text of the weights has been offered in the folder "Experimental Image".

Every time you change the weights, the new weights will be updated in the text.
