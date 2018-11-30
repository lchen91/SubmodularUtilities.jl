# Submodular Utilities

Our implementation was developed under Julia 0.6.2. The algorithms that have been implemented are listed as below.

## Maximization

Submodule: `Maximization`.

- `lazy_greedy`

## Rounding

Submodule: `Rounding`.

- `pipage_round`
- `random_round`

## Multilinear Extension

Submodule: `Multilinear`.

- `get_random_evaluation_of_multilinear_extension`
- `get_random_gradient_of_multilinear_extension`

## Functions

Submodule: `Functions`.

- `get_function_exemplar_based_clustering`: generates objective function of exemplar-based clustering.
- `get_function_active_set_selection`: generates objective function of active set selection.