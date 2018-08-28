{
  "info": {
    "name": "BBC Nitro Get Schema definition",
    "_postman_id": "374e89cc-ed83-4d1e-aec5-17dbf8b5bfc8",
    "description": "Get Schema definition",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "7a3ef883-5d08-49bb-8e08-2e48e6a11c86",
          "name": "getAPI",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get API definition"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "684520f7-e966-4c0d-870d-df6aedf53f80"
            }
          ]
        }
      ]
    },
    {
      "name": "Availabilities",
      "item": [
        {
          "id": "db5d137a-2838-479a-a48f-cffce2c95d52",
          "name": "listAvailability",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/availabilities?availability=%7B%7D&debug=%7B%7D&descendants_of=%7B%7D&media_set=%7B%7D&page=%7B%7D&page_size=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&territory=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Discover details of on-demand availability for programmes and their versions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6aa68b96-45de-4889-bdb0-4dc26ab44b38"
            }
          ]
        }
      ]
    },
    {
      "name": "Broadcasts",
      "item": [
        {
          "id": "676c07c2-8c87-437c-82a2-484461821920",
          "name": "listBroadcasts",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/broadcasts?authority=%7B%7D&descendants_of=%7B%7D&end_from=%7B%7D&end_to=%7B%7D&format=%7B%7D&genre=%7B%7D&id=%7B%7D&item=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&people=%7B%7D&pid=%7B%7D&q=%7B%7D&schedule_day=%7B%7D&schedule_day_from=%7B%7D&schedule_day_to=%7B%7D&service_master_brand=%7B%7D&sid=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&start_from=%7B%7D&start_to=%7B%7D&version=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch metadata about linear Broadcasts and Services, allowing the generation of Television and Radio schedules and other datasets for broadcast items. Use /schedules instead of this feed as it is more efficient. Broadcasts will be deprecated in the future."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99b380cc-2e1a-4d7a-a771-08d4b7d96b26"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "7de9553b-34c3-4972-b0d1-cfb987175266",
          "name": "listGroups",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/groups?embargoed=%7B%7D&for_descendants_of=%7B%7D&for_programme=%7B%7D&group=%7B%7D&group_type=%7B%7D&member=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&q=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Long-lived curated collections of programmes and more, including Collections, Seasons, Franchises and Galleries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70f2ab44-ccc8-478e-81f6-1088601e775d"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "d4b95daa-0797-4ae1-b3b4-773488723125",
          "name": "listImages",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/images?embargoed=%7B%7D&group=%7B%7D&image_type=%7B%7D&is_alternate_image_for=%7B%7D&is_image_for=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&q=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Find metadata for images, particularly those in galleries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33971058-f191-41b9-8a9d-fb40b164edbf"
            }
          ]
        }
      ]
    },
    {
      "name": "Items",
      "item": [
        {
          "id": "f6d53471-dc66-4ce3-a712-d790b479c74d",
          "name": "listItems",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/items?authority=%7B%7D&id=%7B%7D&id_type=%7B%7D&item_type=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&people=%7B%7D&pid=%7B%7D&programme=%7B%7D&q=%7B%7D&segment_event=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Look inside programmes to find segments: chapters, tracks and more"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "def1bf5e-92b9-4341-a172-a33e8521d793"
            }
          ]
        }
      ]
    },
    {
      "name": "Master",
      "item": [
        {
          "id": "f26a86cc-4570-41c1-a65e-2ff07e5e061d",
          "name": "listMasterbrands",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/master_brands?mid=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&q=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all Master Brands"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c6359c9-0788-4fed-8319-c25ae95c5f20"
            }
          ]
        }
      ]
    },
    {
      "name": "People",
      "item": [
        {
          "id": "46b4d409-63eb-4bcc-a621-923ae13de355",
          "name": "listPeople",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/people?authority=%7B%7D&has_external_id=%7B%7D&id=%7B%7D&id_type=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&programme=%7B%7D&q=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The People feed allows you to search for the people and groups that contribute to programmes. This is the starting point for cast and crew credits, as well as finding contributors using external IDs (such as Wikipedia URLs)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e6302be-f596-4745-b9d5-0edf356081aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Pips",
      "item": [
        {
          "id": "eb105403-6e0b-40b9-afff-f4a00d8ea609",
          "name": "listPips",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/pips?page=%7B%7D&page_size=%7B%7D&q=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Look inside pips entities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53ecad0d-3939-41e9-9ff3-5b1633e4a0e7"
            }
          ]
        }
      ]
    },
    {
      "name": "Programme",
      "item": [
        {
          "id": "bc129070-2036-418d-9bc8-eea78e17de2e",
          "name": "listProgrammeDetails",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/programme_details?page=%7B%7D&page_size=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Exposes programme information for a single pid"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1abe4f4c-78c1-4161-ad15-887ddbd11f56"
            }
          ]
        }
      ]
    },
    {
      "name": "Programmes",
      "item": [
        {
          "id": "97276fb7-9fea-4fe4-86ab-ea8e258fcc68",
          "name": "listProgrammes",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/programmes?audio_described=%7B%7D&availability=%7B%7D&availability_entity_type=%7B%7D&availability_from=%7B%7D&availability_type=%7B%7D&children_of=%7B%7D&descendants_of=%7B%7D&duration=%7B%7D&embargoed=%7B%7D&entity_type=%7B%7D&format=%7B%7D&genre=%7B%7D&group=%7B%7D&initial_letter=%7B%7D&initial_letter_end=%7B%7D&initial_letter_start=%7B%7D&initial_letter_strict=%7B%7D&item=%7B%7D&master_brand=%7B%7D&media_set=%7B%7D&media_type=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&payment_type=%7B%7D&people=%7B%7D&pid=%7B%7D&promoted_for=%7B%7D&q=%7B%7D&signed=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&tag_name=%7B%7D&tag_scheme=%7B%7D&tleo=%7B%7D&version=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch metadata about Programmes (brands, series, episodes, clips). By applying different filter restrictions this feed can be used in many ways, for example to retrieve all series belonging to a brand, all the episodes and/or clips for a specific series, or any TLEO objects for a masterbrand. Other filters permit restricting to specific formats and/or genres, and you can request specific versions (for example Signed or Audio-Described). Parameters may be combined in any way suitable for your application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "677dee10-2233-438c-83ad-5edb5823aeed"
            }
          ]
        }
      ]
    },
    {
      "name": "Promotions",
      "item": [
        {
          "id": "b568365f-6998-4a48-abcf-ecb1d407a3e1",
          "name": "listPromotions",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/promotions?context=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&promoted_by=%7B%7D&promoted_for=%7B%7D&q=%7B%7D&status=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Details of short-term editorially curated \"promotions\", for instance those programmes featured on iPlayer today"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77d05c88-b706-49a7-b4f0-912be23459b9"
            }
          ]
        }
      ]
    },
    {
      "name": "Schedules",
      "item": [
        {
          "id": "23855db7-ad22-4074-93c9-e9c4fa1950fc",
          "name": "listSchedules",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/schedules?authority=%7B%7D&descendants_of=%7B%7D&end_from=%7B%7D&end_to=%7B%7D&format=%7B%7D&genre=%7B%7D&group=%7B%7D&id=%7B%7D&id_type=%7B%7D&item=%7B%7D&mixin=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&people=%7B%7D&pid=%7B%7D&q=%7B%7D&repeat=%7B%7D&schedule_day=%7B%7D&schedule_day_from=%7B%7D&schedule_day_to=%7B%7D&service_master_brand=%7B%7D&sid=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&start_from=%7B%7D&start_to=%7B%7D&version=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Dates, Times, Schedules: when and where are programmes being shown?"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b909f4b-025b-410c-8c13-3a6ad2f83c5d"
            }
          ]
        }
      ]
    },
    {
      "name": "Schema",
      "item": [
        {
          "id": "c5de7590-8143-479f-9403-782869dd7beb",
          "name": "getXSD",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/schema",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Schema definition"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c4a59f5-c409-4e37-a126-b2de9bef918a"
            }
          ]
        }
      ]
    }
  ]
}