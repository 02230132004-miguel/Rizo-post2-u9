# Rizo-post2-u9
# ProductListScreen Testing
## Unidad 9 – Testing y Aseguramiento de Calidad en Móvil
### Post-Contenido 2

---

## Descripción del Proyecto

Este proyecto implementa pruebas automatizadas en Flutter para una pantalla de lista de productos (`ProductListScreen`) utilizando arquitectura BLoC.

Se desarrollan pruebas para validar estados de la interfaz, interacción del usuario y consistencia visual mediante golden tests.

---

## Objetivo

Validar el correcto funcionamiento de la pantalla en los siguientes estados:

- Loading  
- Success  
- Error  
- Interacción con botón retry  

Además, asegurar que la interfaz no cambie visualmente mediante golden tests.

---

## Estructura del Proyecto

lib/
├── bloc/
│ └── product_bloc.dart
├── model/
│ └── product.dart
├── repository/
│ └── product_repo.dart
├── screen/
│ └── product_list_screen.dart
├── widget/
│ └── product_card.dart

test/
├── widget/
│ └── product_list_screen_test.dart
├── golden/
│ └── product_card_golden_test.dart
├── goldens/
│ ├── product_card_light.png
│ └── product_card_dark.png


---

## Tests requeridos
- Widget tests: Loading, Success, Error  
- Test de interacción: retry (LoadProducts)  
- Golden tests: tema claro y oscuro  

## Ejecución
flutter test  

## Golden files
Generar o actualizar:
flutter test --update-goldens  

## Entregables
- Repositorio: apellido-post2-u9  
- Estructura completa con tests y goldens  
- Mínimo 3 commits descriptivos  

## Commits
- Agrega widget tests con MockBloc  
- Agrega test de interacción retry  
- Agrega golden tests ProductCard  

