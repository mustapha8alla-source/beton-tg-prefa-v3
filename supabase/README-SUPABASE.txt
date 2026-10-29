SUPABASE — ÉTAPE PRÉPARATOIRE
1. Créez un projet Supabase.
2. Exécutez schema.sql dans SQL Editor.
3. Avant l'utilisation réelle, configurez l'authentification et les politiques Row Level Security (RLS) afin que chaque utilisateur accède uniquement aux centres dont il est membre.
4. Ne mettez jamais la clé service_role dans le navigateur.
5. Ce schéma ne suffit pas à activer la synchronisation. Il faudra intégrer l'authentification, les opérations de lecture/écriture cloud, les contrôles de rôle, la gestion des conflits et la synchronisation hors ligne.
