# PtreeWrapper
Wrapper for booost ptree for easy usage

DataTree tempTree;

tempTree["string"] = "key";

    std::string key = tempTree["string"]


get value by default :

    tempTree["string"].defaults_to<int>(-1);
