# spring-rest-test-sptnk

Сделать war-приложение.
Есть магазин и склад.
И есть одежда, находящаяся либо в магазине, либо на складе.
У каждого экземпляра одежды есть размер, стоимость, цвет, вид и краткое описание.
Размер может быть от 42 до 54.
Цвет может быть белый, синий, красный, зеленый, черный.
Вид одежды может быть платье, брюки, юбка, жилетка, рубашка.
В приложении должен быть сервис, который умеет добавлять данные, отдавать данные, сохранять данные,
перемещать одежду из магазина на склад и со склада в магазин и удалять ее совсем. Базу не надо, сохранение идёт в память.
Нужен REST-контроллер, который выдаёт/принимает данные как JSON и одна страничка html+jquery которая показывает
и даёт редактировать поля: размер, стоимость, цвет, вид и краткое описание, а также кнопки для перемещения данных, сохранения и удаления.
Web-приложение должно запускаться на jboss 7.x или на wildfly 11.x. Java8.
