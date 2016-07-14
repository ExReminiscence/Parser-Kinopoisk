Парсер кинопоиска, который помимо основной информации по фильму, выдаёт ещё и список трейлеров.

Для локального кеша используется Memcached. parser_kinopoisk.php содержит пример использования
Формат выдаваемой информации:
```JSON
{
    "movie": {
        "name": "Мачо и ботан 2",
        "originalname": "22 Jump Street",
        "year": "2014",
        "country_title": "США",
        "slogan": "«Копам под прикрытием крыша не нужна»",
        "actors_main": [
            {
                "name": "Джона Хилл",
                "id": "581340"
            },
            {
                "name": "Ченнинг Татум",
                "id": "475804"
            },
            {
                "name": "Петер Стормаре",
                "id": "6237"
            },
            {
                "name": "Уайатт Расселл",
                "id": "63924"
            },
            {
                "name": "Эмбер Стивенс",
                "id": "37784"
            },
            {
                "name": "Джиллиан Белл",
                "id": "1723738"
            },
            {
                "name": "Айс Кьюб",
                "id": "6721"
            },
            {
                "name": "братья Лукас",
                "id": "2834381"
            },
            {
                "name": "Ник Офферман",
                "id": "9884"
            },
            {
                "name": "Джимми Татро",
                "id": "3146173"
            }
        ],
        "actors_voices": [
            {
                "name": "Роман Бурлаков",
                "id": "1822267"
            },
            {
                "name": "Андрей Кузнецов",
                "id": "1615051"
            },
            {
                "name": "Станислав Концевич",
                "id": "277374"
            },
            {
                "name": "Валерий Соловьев",
                "id": "1079049"
            },
            {
                "name": "Сергей Куприянов",
                "id": "269691"
            }
        ],
        "director": [
            {
                "name": "Фил Лорд",
                "id": "1297700"
            },
            {
                "name": "Кристофер Миллер",
                "id": "30488"
            }
        ],
        "script": [
            {
                "name": "Майкл Бэколл",
                "id": "9989"
            },
            {
                "name": "Орен Узил",
                "id": "1928749"
            },
            {
                "name": "Родни Ротман",
                "id": "1096334"
            }
        ],
        "producer": [
            {
                "name": "Джона Хилл",
                "id": "581340"
            },
            {
                "name": "Нил Х. Мориц",
                "id": "52"
            },
            {
                "name": "Ченнинг Татум",
                "id": "475804"
            }
        ],
        "operator": [
            {
                "name": "Бэрри Петерсон",
                "id": "611940"
            }
        ],
        "composer": [
            {
                "name": "Марк Мазерсбо",
                "id": "27000"
            }
        ],
        "genre": [
            {
                "title": "комедия",
                "id": "6"
            },
            {
                "title": "боевик",
                "id": "3"
            },
            {
                "title": "криминал",
                "id": "16"
            }
        ],
        "rus_charges": "  1.48 млн",
        "world_premiere": "5 июня 2014",
        "rus_premiere": "3 июля 2014",
        "time": "112 мин. / 01:52",
        "description": "Офицерам Шмидту и Дженко теперь предстоит работать под прикрытием в местном колледже. Однако когда Дженко встречает родственную душу в футбольной команде, а Шмидт проникает в богемную среду, они начинают сомневаться в их товариществе",
        "imdb": "7.30 (112 583)",
        "kinopoisk": "6.826",
        "poster_url": "http://www.kinopoisk.ru/images/film_big/672899.jpg",
        "trailer_url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192369.mp4",
        "trailers": [
            {
                "title": "Трейлер №3",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-215247.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-215249.mp4",
                        "quality": "Среднее качество"
                    }
                ]
            },
            {
                "title": "Международный трейлер",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-210639.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-210638.mp4",
                        "quality": "Среднее качество"
                    }
                ]
            },
            {
                "title": "Red-band трейлер №2 (украинский язык)",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-210128.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-210129.mp4",
                        "quality": "Среднее качество"
                    }
                ]
            },
            {
                "title": "Red-band трейлер №2",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-206333.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-206334.mp4",
                        "quality": "Среднее качество"
                    }
                ]
            },
            {
                "title": "Трейлер №2",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-199639.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-199640.mp4",
                        "quality": "Среднее качество"
                    }
                ]
            },
            {
                "title": "Трейлер (украинский язык)",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-213121.mp4",
                        "quality": "Среднее качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-213122.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-213124.mp4",
                        "quality": "Низкое качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-213126.mp4",
                        "quality": "Среднее качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-213128.mp4",
                        "quality": "Высокое качество"
                    }
                ]
            },
            {
                "title": "Трейлер (дублированный)",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192372.mp4",
                        "quality": "Среднее качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192367.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192370.mp4",
                        "quality": "Низкое качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192368.mp4",
                        "quality": "Среднее качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192369.mp4",
                        "quality": "Высокое качество"
                    }
                ]
            },
            {
                "title": "Red-band трейлер (русский язык)",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192260.mp4",
                        "quality": "Низкое качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192238.mp4",
                        "quality": "Среднее качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192239.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192240.mp4",
                        "quality": "Низкое качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-192241.mp4",
                        "quality": "Среднее качество"
                    }
                ]
            },
            {
                "title": "Трейлер",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-194186.mp4",
                        "quality": "Среднее качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-194182.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-194183.mp4",
                        "quality": "Низкое качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-194184.mp4",
                        "quality": "Среднее качество"
                    },
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-194185.mp4",
                        "quality": "Высокое качество"
                    }
                ]
            },
            {
                "title": "Red-band трейлер",
                "sd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-191181.mp4",
                        "quality": "Высокое качество"
                    }
                ],
                "hd": [
                    {
                        "url": "http://kp.cdn.yandex.net/672899/kinopoisk.ru-22-Jump-Street-191182.mp4",
                        "quality": "Среднее качество"
                    }
                ]
            }
        ]
    }
}
```
