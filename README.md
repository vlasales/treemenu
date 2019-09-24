# treemenu

Naprogramujte řešení výpisu stromové struktury menu (neomezené zanořování) jak veřejnou (výpis do HTML), tak administrační část (možnost přidání/editace/mazání kategorie). Do administrační části se dostanete přes odkaz „Sign in“.

Přístupové údaje: Username: admin Password: admin 

Každá položka v menu musí mít jednoznačný identifikátor. Používejte i optimalizaci počtu a rychlosti SQL dotazů a cyklů ve scriptu. Chceme dosáhnout následující struktury a libovolného směrového posunu kategorií nahoru/dolů v rámci úrovně a jejich možného přemístění do jiné úrovně. 

    • první úroveň 1 
        ◦ druhá úroveň 1a 
        ◦ druhá úroveň 1b
            ▪ třetí úroveň 1c 
                • čtvrtá úroveň 1d 
            ▪ třetí úroveň 1e 
                • čtvrtá úroveň 1f 
                    ◦ pátá úroveň 1g
                        ▪ šestá úroveň 1h 
                        ▪ šestá úroveň 1h 
                        ▪ šestá úroveň 1i 
                    ◦ pátá úroveň 1j 
            ▪ třetí úroveň 1k
        ◦ druhá úroveň 1l 
    • první úroveň 2
        ◦ druhá úroveň 2a 
            ▪ třetí úroveň 2b
        ◦ druhá úroveň 2c 
