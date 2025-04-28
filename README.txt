RAVeOscGEn

L’outil Max4Live repose sur une approche hybride visant à faciliter l’interaction expressive avec le modèle RAVE. Il se structure
autour de plusieurs modules principaux :

	• un contrôle direct de plusieurs dimensions de l’espace
	latent du modèle ;

	• un module d’enveloppe permettant de sculpter l’évolution
	temporelle du son ;

	• un module oscillateur agissant comme source d’inférence
	dynamique ;
	
	• un multiplicateur de couches (layers) offrant la possibilité
	d’épaissir la texture sonore ;
	
	• un contrôle de niveau de base (base level) garantissant une
	activité sonore constante

--Exemples de création musicale

Akousmogram - zchrdy
https://on.soundcloud.com/Miqz76phyfLVkQoDA


--Installation

Télécharger le fichier RAVeOscGEn.amxd

Suivre les directives d'installation de nn~ sur le site web de l'IRCAM:

https://forum.ircam.fr/projects/detail/nn/

Lien vidéo pour l'installation de nn~:

https://youtu.be/Dy1WTc022rQ?t=37



Il est nécessaire d'avoir des modèles nn~ pour utiliser l'instrument

Voici quelques modèles disponible à télécharger

Modèles IRCAM:
https://acids-ircam.github.io/rave_models_download

Modèles Instruments Lab:
https://huggingface.co/Intelligent-Instruments-Lab/rave-models



--Utilisation

Pour commencer à utiliser le Max4Live device, il faut tout d'abord glisser les modèles dans les champs appropriés 

Ensuite il ne suffit que d'appuyer sur une note midi pour lancer l'enveloppe


Ableton: 

Glisser le fichier dans un canal MIDI ou Audio dans Ableton Live avec Max for Live

Requis : Ableton Live version X.X+ avec Max for Live activé


Max MSP:

Simplement ouvrir le fichier dans l'application Max

Requis : Max 8



--Paramètres et Contrôles

-Oscillator

	OSC CTL pour activer l'oscillateur et le transfert de timbre	

	Waveform pour affecter le timbre de simple à complexe

	Noise pour injecter du bruit blanc ou rose
	
	PITCH MODULATION pour moduler la fréquence

	WAVE MOD pour moduler la forme d'onde

-MODIFIERS

	Enveloppe principale
	
	LOOP pour looper l'enveloppe

	ENV TO LAYERS pour moduler le modèle

	BASE LEVEL pour faire jouer les modèles en continu

	LAYER MULT pour multiplier les valeurs appliquées aux modèles

	FILTER est un filtre passe-bas résonant qu'on peut appliquer soit sur l'Oscillateur (PRE) ou sur la sortie des modèles (POST)

-LAYER CTL

	Interface 2D pour se déplacer à travers la mémoire latente des modèles

	Il doit être activé avec le bouton LAYER CTL sinon les valeurs ne sont pas affectées

_____________________________________________________________________________________

Outil développé par Zachary Hardy et Mahault Sampy à l'Université de Montréal dans le cadre du séminaire Projet en intelligence artificielle musicale en 2025



