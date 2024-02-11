<details>
  <summary> Mô tả bộ dữ liệu </summary> 

1. Id: Đây là một số duy nhất gán cho mỗi mục nhập trong tập dữ liệu. 
2. `MSSubClass`: Đây là loại của ngôi nhà và đại diện cho một loạt các tính năng liên quan đến loại cấu trúc. Ví dụ, một giá trị "60" có thể đại diện cho một ngôi nhà loại 2 tầng trở lên.
3. `MSZoning`: Đây là phân khu của ngôi nhà, nó cho biết khu vực dự định sử dụng ngôi nhà, chẳng hạn như khu dân cư thương mại (Commercial) hoặc khu dân cư loại A (Agriculture).
4. `LotFrontage`: Độ rộng của lô đất ở phía đường. Đây là chiều rộng của mặt tiền của lô đất.
5. `LotArea`: Diện tích của lô đất trong đơn vị thước vuông (square feet).
6. `Street`: Loại đường trước nhà (ví dụ, ngõ đường (Grvl) hoặc đường nhựa (Pave)).
7. `Alley`: Loại hẻm trước nhà (nếu có) có thể là hẻm cát (Grvl), hẻm đường (Pave) hoặc không có (NA).
8. `LotShape`: Hình dạng của lô đất (ví dụ, hình chữ nhật, hình trái tim, hình bán nguyệt, hình vuông).
9. `LandContour`: Độ cao của đất trong lô (nền đất phẳng, phẳng hạ, cao lên hoặc thấp đi).
10. `Utilities`: Tiện ích công cộng có sẵn cho ngôi nhà (ví dụ, điện, nước, cống thoát).
11. `LotConfig`: Cách mà lô đất được cấu hình trong khu vực (ví dụ, góc đường, lô đất nằm giữa khối, lô đất gần biển, v.v.).
12. `LandSlope`: Độ dốc của đất (nền đất phẳng, nền đất trung bình, nền đất dốc).
13. `Neighborhood`: Khu phố (khu vực) trong đó ngôi nhà nằm. Điều này có thể ảnh hưởng đến giá trị của ngôi nhà do sự quyết định về vị trí.
14. `Condition1` và `Condition2`: Điều kiện xung quanh ngôi nhà, ví dụ như cự ly đến các tính năng như đường sắt hoặc dòng nước.
15. `BldgType`: Loại kiến trúc của ngôi nhà (ví dụ, nhà 1 tầng, nhà 1 tầng và ½, nhà hàng loạt, v.v.).
16. `HouseStyle`: Phong cách của ngôi nhà (ví dụ, ngôi nhà hai tầng, ngôi nhà dạng biệt thự, ngôi nhà dạng cấu trúc mút, v.v.).
17. `OverallQual`: Chất lượng tổng thể của ngôi nhà (được đánh giá bằng điểm số từ 1 đến 10, với 10 là chất lượng tốt nhất).
18. `OverallCond`: Tình trạng tổng thể của ngôi nhà (được đánh giá bằng điểm số từ 1 đến 10, với 10 là tình trạng tốt nhất).
19. `YearBuilt`: Năm xây dựng ngôi nhà.
20. `YearRemodAdd`: Năm cải tạo gần đây của ngôi nhà.
21. `RoofStyle` và `RoofMatl`: Loại mái và vật liệu mái của ngôi nhà.
22. `Exterior1st` và `Exterior2nd`: Vật liệu ngoại thất chính và thứ cấp của ngôi nhà.
23. `MasVnrType`: Loại vật liệu vân nổi ngoại trang.
24. ``MasVnrArea``: Diện tích vân nổi ngoại trang trên ngôi nhà.
25. `ExterQual` và `ExterCond`: Chất lượng và tình trạng ngoại thất của ngôi nhà.
26. `Foundation`: Loại nền móng của ngôi nhà.
27. `BsmtQual`, `BsmtCond`, `BsmtExposure`, `BsmtFinType1`, và `BsmtFinType2`: Các thuộc tính liên quan đến tầng hầm (chất lượng, tình trạng, tiếp xúc với ngoài, loại hoàn thiện, v.v.).
28. `BsmtFinSF1`, `BsmtFinSF2`, `BsmtUnfSF`, và `TotalBsmtSF`: Diện tích hoàn thiện, diện tích không hoàn thiện và tổng diện tích của tầng hầm.
29. `Heating`: Hệ thống sưởi ấm trong ngôi nhà.
30. `HeatingQC`: Chất lượng hệ thống sưởi ấm.
31. `CentralAir`: Sự hiện diện của hệ thống điều hòa không khí trong ngôi nhà (có hoặc không có).
32. `Electrical`: Loại hệ thống điện trong ngôi nhà (ví dụ, hệ thống điện một pha hoặc ba pha).
33. `1stFlrSF`: Diện tích của tầng trệt (tầng 1) trong đơn vị thước vuông (square feet).
34. `2ndFlrSF`: Diện tích của tầng 2 trong đơn vị thước vuông (square feet).
35. `LowQualFinSF`: Diện tích của tầng hầm có chất lượng kém trong đơn vị thước vuông (square feet).
36. `GrLivArea`: Diện tích sống chung trên mức đất (tổng diện tích sống trên tất cả các tầng).
37. `BsmtFullBath` và `BsmtHalfBath`: Số lượng phòng tắm đầy và bán trong tầng hầm.
38. `FullBath` và `HalfBath`: Số lượng phòng tắm đầy và bán trên tầng chính.
39. `BedroomAbvGr`: Số lượng phòng ngủ trên tầng chính (không tính phòng ngủ trên tầng hầm hoặc tầng 2).
40. `KitchenAbvGr`: Số lượng căn bếp trên tầng chính.
41. `KitchenQual`: Chất lượng của căn bếp (ví dụ, phòng bếp tiêu chuẩn, phòng bếp tiêu chuẩn với cửa sổ, v.v.).
42. `TotRmsAbvGrd`: Tổng số phòng trên tầng chính (không tính phòng tắm).
43. `Functional`: Sự cố gắng và chức năng của ngôi nhà (ví dụ, hoạt động bình thường, cơ bản cần sửa chữa, v.v.).
44. `Fireplaces`: Số lượng lò sưởi trong ngôi nhà.
45. `FireplaceQu`: Chất lượng của lò sưởi.
46. `GarageType`: Loại garage (ví dụ, garage cố định, garage ngoài trời, garage không mái che, v.v.).
47. `GarageYrBlt`: Năm xây dựng garage.
48. `GarageFinish`: Tình trạng hoàn thiện của garage (ví dụ, hoàn thiện, gần hoàn thiện, không hoàn thiện).
49. `GarageCars`: Số lượng xe ô tô mà garage có thể chứa.
50. `GarageArea`: Diện tích của garage trong đơn vị thước vuông (square feet).
51. `GarageQual` và `GarageCond`: Chất lượng và tình trạng của garage.
52. `PavedDrive`: Loại lối vào đường bê tông (P), đường nhựa (Y) hoặc không có đường (N).
53. `WoodDeckSF`: Diện tích của sàn nhà ngoài trời (deck) bằng gỗ trong đơn vị thước vuông (square feet).
54. `OpenPorchSF`: Diện tích của sân hiên mở trong đơn vị thước vuông (square feet).
55. `EnclosedPorch`: Diện tích của sân hiên kín trong đơn vị thước vuông (square feet).
56. `3SsnPorch`: Diện tích của sân hiên ba mùa trong đơn vị thước vuông (square feet).
57. `ScreenPorch`: Diện tích của sân hiên với màn hình trong đơn vị thước vuông (square feet).
58. `PoolArea`: Diện tích của hồ bơi trong đơn vị thước vuông (square feet).
59. `PoolQC`: Chất lượng của hồ bơi.
60. `Fence`: Loại hàng rào xung quanh ngôi nhà (ví dụ, hàng rào gỗ, hàng rào dây thép, v.v.).
61. `Misc Feature`: Các tính năng khác không được quy định trong danh sách, chẳng hạn như lối vào cho xe hơi hoặc hình tròn.
62. `MiscVal`: Giá trị của các tính năng khác (nếu có).
63. `MoSold`: Tháng mà giao dịch bất động sản được thực hiện.
64. `YrSold`: Năm mà giao dịch bất động sản được thực hiện.
65. `SaleType`: Loại giao dịch (ví dụ, bán qua môi giới, bán trực tiếp, v.v.).
66. `SaleCondition`: Tình trạng của giao dịch (ví dụ, bán thường, bán nhanh, v.v.).
67. `SalePrice`: Giá bán của ngôi nhà, đây là biến mục tiêu mà bạn muốn dự đoán hoặc phân tích.
</details>
