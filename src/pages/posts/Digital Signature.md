https://fr.wikipedia.org/wiki/Signature_numérique
==Qu'est ce qu'une Signature Digital ?==
	Permet d'**authentifier l'auteur d'un document électronique** et garentir la [[Non-repudiation]]
==Pourquoi utiliser une  Signature Digital  ?==
1. Authentique
2. Infalsifiable
3. Non réutilisable 
4. Inaltérable
5. Irrévocable
L'essentiel des procédures de signature numérique s'appui sur [[Asymmetric Algorithm Chiffrement]]
==Quand utiliser une  Signature Digital  ?==
Doit permettre au. lecteur d'un documennt d'identifier la personne ou l'organisme qui a appos" sa signature
Garentirr que le document n'a pas été altéré entre l'instant ou l'auteur l'a signé et le moment ou le lecteur consulte
==Comment ça marche une  Signature Digital  ?==
	Comment verifier que la clé viens vraiment du signataire ?
		Le receveur va hasher la donné reçu en une nouvelle valeur
		après vérification que le signataire certificat est valide, la public key décrypte(vérifies)la digital signature
		Et pour finir la nouvelle valeur afficher sera comparer au hashing qui aura ete fait dans la première etape.
		Si ils sont similaires, on saura que les informations n'auront pas été changer
	

![[Pasted image 20240116112535.png]]
