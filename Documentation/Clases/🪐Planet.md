## BASIC

int Id (Key)
String Name
int Diameter (1)
int TempMin
int TempMax
int HasRings

## RESOURCES

### Basic Resources
// Todos disponibles en todos los planetas

int BaseMetal // Producción base de metal
int MaxMetal
int Metal

int BaseCrystal
int MaxCrystal
int Crystal

int BaseDeuterium
int MaxDeuterium
int Deuterium

### Exotic Resources
// Sólo uno de los posibles por planeta

[[ExoticResource]]? ExoticResource
int BaseExoticResource
int MaxExoticResource
int ExoticResource

int EnergyProduction

### Advanced  Resources
// Se refinan/fabrican a partir de los básicos y exóticos 
[[AdvancedResource]]


## RELATIONSHIPS

User User

IEnumerable(Moon) Moons

## GAMEPLAY FLAGS








(1) : May be related to a "Size" and/or have min and max, so can be translated into small, medium or big planet
