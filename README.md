Fatturazione attiva
=======

Tabelle
* ACPM
 * tbkey: String 32  PK
 * tbdati: String 256
* ACTP
 * tbkey: String 32 PK
 * tbdati: String 256
* Clienti
 * ancoco: String 32 PK
 * ancofs: String 64
 * anpaiv: String 16
 * aninco: String 256
 * anpefi: boolean
 * anista: String 2
 * invia: String 64
 * innaz: String 8
 * insta: String 8
 * incit: String 64
 * inpro: String 2
 * incap: String 8
 * provenienza: String 2
 * tipopag: String 32
 * condpag: String 32
 * codresa: String 32
 * codbanca: String 32
 * desbanca: String 128
 * codabi: String 8
 * codcab: String 8
 * numconto: String 32
 * societa: String 5
* ClientiDiapason
 * ancoco: String 16
 * hvr0001: String 2
 * ancofs: String 16
 * anpaiv: String 32
 * aninco: String 256
 * anpefi: String 32
 * anista: String 8
 * invia: String 64
 * innaz: String 8
 * insta: String 8
 * incit: String 64
 * inpro: String 2
 * incap: String 8
 * oavpayt: String 8
 * oavpyac: string 8
* NumeratoreClienti
 * integer 
* OCSAGTV
 * oavtype: String 2
 * oavkeyg: String 8 PK
 * oavcosc: String 5
 * oavseq: Integer
 * oavvsdt: Integer
 * oavvedt: Integer
 * oavcurr: String 8
 * oavqual: String 16
 * oavpack: String 8
 * oavpayt: String 8
 * oavpayc: String 8
 * oavship: String 8
 * oavassi: String 8
 * oavgara: String 8
 * oavapdt: Integer
 * oavtpcg: String 4
 * oavspin: String 4
 * oavrclf: String 4
 * oavrcsf: String 4
 * oavspf1: String 4
 * oavspf2: String 4
 * oavspf3: String 4
 * oavfamm: String 4
 * oavpgev: String 4
* Società
 * societa: String 8 PK
 * descrizione: String 32
* TestataFattura
 * id Serial PK
 * batch_code: String 
 * societa_fk: String 8
 * negozio: String 8
 * data_delivery_n: Date
 * delivery_n: String 32
 * vr_fr: String 4
 * tipo_documento: String
 * ancoco_fk: String 32
 * imponibile: Float
 * imposta: Float
 * sconto: Float
 * anticipo: Float
 * annotazioni: String 1024
 * contabilizzata: Boolean
 * confermata: Boolean
 * annullata: Boolean
 * data_fattura: Date
 * numero_fattura: Integer
 * note_in_fattura: String 256
 * ordine: Strng 1024
 * riga_aggiuntiva: String 256
 * flag_raggruppa: Boolean
 * dati_ddt_raggruppata: String 1024
 * tipo_pagamento: String 8
 * cond_pagamento: String 8
 * numero_interno: String 32
* RigaDattura