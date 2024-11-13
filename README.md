# new_service
Projekt Repozytorium

## Instrukcje dotyczące pracy z repozytorium

### Jak pobrać repozytorium

#### Aby pobrać repozytorium z GitHub użyj polecenia git clone. Najpierw skopiuj URL repozytorium (z przycisku Code na GitHubie) i w terminalu wykonaj:

git clone https://github.com/username/repo-name.git

### Nawigowanie po gałęziach:
#### W Git możesz pracować na różnych gałęziach (branches). Aby zobaczyć dostępne gałęzie w repozytorium:
git branch

#### Aby przełączyć się na inną gałąź:
git checkout nazwa_gałęzi

#### Aby utworzyć nową gałąź i od razu na nią przejść:
git checkout -b nowa_gałąź

### Przywracanie wcześniejszych wersji dokumentów:

#### Jeśli chcesz przywrócić wcześniejszą wersję pliku lub gałęzi, możesz to zrobić za pomocą polecenia git checkout. Jeśli znasz nazwę commita, do którego chcesz wrócić, użyj:
git checkout <commit_id> -- <ścieżka_do_pliku>

#### Możesz także przywrócić całą gałąź do poprzedniego commita:
git reset --hard <commit_id>

### Praca z zdalnym repozytorium:
Aby pobrać najnowsze zmiany z zdalnego repozytorium:
git pull origin main

#### Aby wysłać swoje zmiany do repozytorium zdalnego:
git push origin main

## Informacje o wykorzystanych poleceniach GIT i ich zastosowaniach
### Dodawanie plików:
#### Aby dodać plik do systemu Git i przygotować go do zatwierdzenia (commit):
git add nazwa_pliku

#### Aby dodać wszystkie zmienione pliki:
git add .

### Tworzenie gałęzi:
Aby stworzyć nową gałąź, użyj:
git branch nowa_gałąź


#### Aby przejść na nowo utworzoną gałąź:
git checkout nowa_gałąź

### Scalanie gałęzi:
Aby scalić jedną gałąź (np. feature-branch) do gałęzi głównej (main):

#### Najpierw upewnij się, że jesteś na gałęzi, do której chcesz dodać zmiany (np. main):
git checkout main

#### Następnie scal gałęzie:
git merge feature-branch

### Zatwierdzanie zmian:
#### Aby zatwierdzić zmiany w lokalnym repozytorium:
git commit -m "Opis zmian"
