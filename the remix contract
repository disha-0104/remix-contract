
// SPDX-License-Identifier: MIT

pragma solidity ^0.8.13;

contract vendor{
    int netPrice;
    int salesPrice;


constructor() {
    netPrice = 0;
    salesPrice=0;
}



    function checkProfit(int good, int bad, int price) public {
        int totalVege = good + bad;
        netPrice= totalVege * price;
        salesPrice = good*(20 + price)- netPrice;
    }
    
    

    function getResult() public view returns(int){
        return salesPrice;
    }

}
