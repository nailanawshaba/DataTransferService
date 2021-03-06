---

copyright:
  years: 1994, 2018
lastupdated: "2018-05-22"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}

# Foire aux questions

## Qu'est-ce qu'un transfert de données ?

Ce service permet à des utilisateurs autorisés (généralement l'administrateur du compte) d'envoyer des périphériques compatibles vers l'un de nos centres de données pour qu'ils se connectent directement au réseau du compte. Le périphérique est hébergé dans une armoire dédiée et est monté comme cible iSCSI pendant deux semaines. Au cours de cette période, l'administrateur peut accéder au périphérique sur le réseau pour pouvoir utiliser les autres périphériques et/ou services sur le compte. A l'issue de cette période, une extension peut être demandée pour que le périphérique reste connecté sur le réseau. Sinon, il est renvoyé à l'adresse spécifiée dans la demande, ou détruit sur site. 

## Puis-je expédier un périphérique pour transfert de données à l'étranger ?

Le matériel et les disques peuvent être expédiés à l'échelle nationale et internationale vers n'importe lequel de nos centres de données. Toutefois, le client est responsable des points suivants : 

- S'assurer qu'aucune licence d'importation ou d'exportation n'est requise pour expédier le périphérique vers le centre de données {{site.data.keyword.IBM}} ou pour lerenvoyer au client (le cas échéant). 
- S'assurer que ni le client ni un utilisateur du client dont les données sont incluses dans le contenu ne sont soumis à une ordonnance du gouvernement américain leur refusant ou leur révoquant leurs droits d'exportation. Vous devez avertir {{site.data.keyword.IBM}} immédiatement si votre entreprise ou un tel utilisateur devient soumis à ce type d'ordonnance.
- Effectuer toutes les démarches de licence, d'expédition et de dédouanement liées au périphérique, y compris le paiement des frais de douane, taxes et autres frais d'expédition pour faire parvenir le périphérique au centre de données {{site.data.keyword.IBM}} et éventuellement l'en faire revenir.
- Observer toutes les lois applicables, notamment en matière de protection des données, d'importation et d'exportation, en ce qui concerne l'expédition et le retour du périphérique et le transfert du contenu vers le centre de données {{site.data.keyword.IBM}}.
- Avoir mis en place des accords appropriés, et obtenu tous les droits nécessaires, avec l'utilisateur du client en ce qui concerne le transfert matériel des données de l'utilisateur le client.

Inclure une étiquette de retour prépayée, ainsi que tous les documents d'exportation appropriés dans le colis si vous souhaitez que le périphérique vous soit réexpédiés. Si aucune demande de retour n'est formulée, le périphérique sera détruit. 


## Quels types de périphérique puis-je envoyer avec une demande de transfert de données ?
Suivez les instructions ci-après lorsque vous sélectionnez un périphérique ou un disque (CD ou DVD) à des fins de transfert de données :

- Exigences liées au matériel :
   - Alimentation électrique compatible 208v/220v.

   - Alimentation électrique compatible avec une prise de courant 120v standard (NEMA 5-15P).

   - Périphérique compatible USB 2.0 ou USB 3.0.

   - Présence d'un connecteur mâle USB (USB standard installé sur la plupart des ordinateurs).

- Exigences liées aux CD/DVD :

   - Les disques doivent être livrés dans des boîtes de rangement pour CD, boîtiers ou autres conteneurs similaires. Si vous souhaitez envoyer plusieurs disques, rangez-les ensemble dans un même support.

   - Chaque disque doit être étiqueté clairement et de manière unique (par exemple, Disque A, Disque B, Disque C, etc.)

## Mon périphérique peut-il m'être renvoyé plus rapidement ou doit-il rester connecté plus longtemps ?

Oui, votre matériel ou vos disques peuvent être renvoyés n'importe quand ou peuvent rester connectés plus longtemps si besoin. Si vous souhaitez demander une extension, ajoutez un commentaire au ticket de demande de transfert de données d'origine en indiquant clairement votre demande. Si vous demandez le retour, nous procéderons à la déconnexion et au renvoi du matériel ou des disques à l'adresse d'expédition que vous avez renseignée dans la demande d'origine en utilisant l'étiquette prépayée et le colis fournis.

Si vous souhaitez prolonger la durée de conservation, la demande d'extension sera traitée dans les plus brefs délais. Il est important de noter que chaque demande d'extension rallonge d'une semaine la période pendant laquelle le périphérique est connecté et peut être subordonnée à des frais additionnels. Tous les renseignements nécessaires vous seront fournis par notre équipe dans la réponse du ticket d'origine.

## Que signifie chaque statut figurant sur mon ticket de transfert de données ?

Chaque statut figurant sur le ticket de transfert de données indique la phase du processus de transfert pour le matériel ou les disques envoyés au centre de données. Pour en savoir plus sur chaque statut, consultez le tableau ci-après :

|Statut 	| Définition |
|---------| -----------|
|Envoyé à SoftLayer 	|La demande de transfert de données a été soumise par l'utilisateur, et le matériel ou les disques sont en cours de livraison vers le centre de données sélectionné.|
|Reçu par SoftLayer |	Le colis a été livré au centre de données, un numéro de série a été attribué au périphérique et celui-ci a été scanné dans notre système.|
|Connexion |	Le matériel ou le disque est connecté au périphérique. |
|Connecté |	Une cible iSCSI a été créée pour le périphérique. |
|Demande d'extension |L'utilisateur a demandé une extension des deux semaines de connexion.|
|Demande de retour |L'utilisateur a demandé le retour de son matériel ou de ses disques.|
|Déconnexion |	Une déconnexion du matériel ou des disques a été initiée. |
|Déconnecté |	La cible a été correctement déconnectée. |
|Détruit |Le périphérique a été détruit sur site conformément à la procédure de destruction des unités de disques durs.|
|Renvoyé par SoftLayer |	Le matériel ou les disques ont été emballés et expédiés à l'adresse de retour fournie dans la demande d'origine.|
