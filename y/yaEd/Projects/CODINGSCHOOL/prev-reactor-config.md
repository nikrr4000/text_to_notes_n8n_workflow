```json
{
    "queue": "CODINGSCHOOL",
    "condition": {
        "from_status": "registrationInLMS",
        "to_status": "firststep",
        "group": "students"
    },
    "double": {
        "status": {
            "name": "Закрыт",
            "key": "closedMeta"
        },
        "conditions": [
            {
                "condition": "\"Телефон\": \"{}\"",
                "params": [
                    "mobilnyjTelefon"
                ]
            },
            {
                "condition": "\"Email 1\": \"{}\"",
                "params": [
                    "email"
                ]
            }
        ]
    },
    "course_fork": {
        "Сербия": {
            "course_id": 1178,
            "invite_id": 1056
        },
        "Армения": {
            "course_id": 1182,
            "invite_id": 1055
        },
        "Казахстан": {
            "course_id": 1181,
            "invite_id": 1054
        },
        "Кыргызстан": {
            "course_id": 1181,
            "invite_id": 1054
        },
        "Узбекистан": {
            "course_id": 1255,
            "invite_id": 1139
        }
    }
}
```