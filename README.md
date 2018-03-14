# Currency-Exchange-Smart-Contract
currency exchange monitoring API
pragma solidity ^0.4.6;

contract SimpleStorage
{
    uint storeData;
    bool var1;
    
    //function set(uint x)
    function set(bool x)
    {
        //storeData = x;
        var1 = x;
        
    }
    
    //function get() constant returns (uint retVal)
    function get() constant returns (bool retVal)
    {
        return var1;
        
    }
}
