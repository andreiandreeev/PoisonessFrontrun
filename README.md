Данный проект -- смарт-контракт на языке solidity для блокчейна Ethereum.
Основная идея -- ловушка для Front-run атак.
Это обычный токен ERC20, который в обычных случаях ведет себя так же, как и любой другой токен ERC20. Однако у него есть особая логика для обнаружения, когда кто-либо, кроме указанного владельца совершает транзакцию, и в этих ситуациях он возвращает только 10% от указанной суммы/
