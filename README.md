# MITWConnecthon2021
MITW2021_Results_Documentation
參與聯測項目:
Track#1 , Track#6
參與日期：11月1日 - 11月3日
測試項目:
1. MolecularSequence Creator 
    - MolecularSequence JSON 資料的建立 與 上傳
2. Observation Creator
    - Observation JSON 資料的建立 與 上傳
3. Observation consumer
    - 透過輸入病人ID 查詢病人Patient resource資料（managingOrganization，identifier）
    - 透過輸入病人ID 查詢病人樣本Specimen resource資料
    - 透過輸入component-code-value （HGNC:14825）查詢Observation中所輸入的GeneStudied的資料
    - 透過輸入病人ID , Specimen ID, component-code-value 查詢特定病人在特定樣本下的基因定序Observation resource 資料

通過項目:
-MolecularSequence creator
-Observation creator
-Observation consumer

未來發展項目:
-在確認用戶立場後，可進行UI優化（明確的requiredField）或 讓使用者自行選擇資料來源
