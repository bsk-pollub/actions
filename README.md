# Zadanie 2
## Bartłomiej Skorek

# Pytanie 1 - GitHub Actions + BuildKit

Zrealizowane z użyciem pliku [build1.yml](https://github.com/bsk-pollub/actions/blob/master/.github/workflows/build1.yml) - buduje kontener z uzyciem BuildKita oraz wstawia go na DockerHub.

# Pytanie 2 - Architektury

Zrealizowane z użyciem pliku [build2.yml](https://github.com/bsk-pollub/actions/blob/master/.github/workflows/build2.yml) - buduje kontener tak jak w zadaniu 1, ale dla wielu architektur.

# Pytanie 3 - Wieloetapowosc

Zrealizowane z użyciem pliku [build3.yml](https://github.com/bsk-pollub/actions/blob/master/.github/workflows/build3.yml) - buduje obraz wieloetapowo - to nie wymaga specjalnego wysilku, poniewaz BuildKit wspiera to natywnie.
Wykorzystano plik testowy 'Dockerfile.z2', a reszta skryptu jest skopiowana z poprzednich pytań.
