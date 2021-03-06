﻿
|AGID_logo_carta_intestata-02.png|
   
+---------------------------------------------------------------------------------------------------+
| **SPECIFICHE ATTUATIVE DEI CODICI IDENTIFICATIVI DI VERSAMENTO, RIVERSAMENTO E RENDICONTAZIONE**  |
|                                                                                                   |
|                                                                                                   |
| *Allegato A alle "Linee guida per l'effettuazione dei pagamenti elettronici a favore delle*       |
| *pubbliche amministrazioni e dei gestori di pubblici servizi"*                                    |
|                                                                                                   |
|                                                                                                   |
| **Versione 1.3.1 - gennaio 2018**                                                                 |
+---------------------------------------------------------------------------------------------------+

.. _riconciliazione-del-flusso-di-riversamento:

8. Riconciliazione del flusso di riversamento  |image19| 
=============================================

La riconciliazione del riversamento effettuato dal prestatore di servizi
di pagamento avviene a cura dell’Ente Creditore prendendo in
considerazione la componente **<idFlusso>** della causale del SEPA
Credit Transfer con il quale è stato effettuato il riversamento verso
l’Ente Creditore (:ref:`vedi capitolo 6 <riversamento-agli-enti-creditori>`) ed il dato identificativoFlusso
presente nel flusso di rendicontazione di cui al :ref:`capitolo 7 <flusso-di-rendicontazione>`.

Come riscontro, il dato importoTotalePagamenti del flusso di
rendicontazione dovrà coincidere con il dato *Amount* (attributo AT-04)
del suddetto SCT di riversamento.

Se ritenuto opportuno, in questa fase l’Ente Creditore può verificare la
corrispondenza del dato identificativoUnivocoRegolamento o con il dato
*Transaction Reference Number* (TRN, attributo AT-43 Originator Bank’s
Reference) oppure con il dato *End To End Id* (attributo AT-41
Originator’s Reference to the Credit Transfer) del suddetto SCT di
riversamento.



.. |AGID_logo_carta_intestata-02.png| image:: media/header.png
   :width: 5.90551in
   :height: 1.30277in
.. |image19| image:: media/image7.png
   :width: 0.7874in
   :height: 0.22905in
