# Vehkamäki Moose ID
Riistakamerahavaintojen ja hirviyksilöiden seurantasovellus.

## Toiminnot
- Supabase Auth -kirjautuminen
- yksityinen riistakamerakuvien tallennus
- havaintojen, sarvitietojen ja ikäarvioiden kirjaaminen
- yksilörekisteri
- tietokantarakenne Season-ID / Lifetime-ID AI-tunnistukselle
- pgvector + HNSW valmiina 768-ulotteisille embedding-vektoreille

## Kehitys
Kopioi .env.example tiedostoksi .env.local ja täytä Supabase-arvot.
`npm install`
`npm run dev`
