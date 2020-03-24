# mock-data
Mock Data


{
  "task_config": [
    {
      "id": 1,
      "name": "Verify RC",
      "cta": "FORM_SUBMIT"
    },
    {
      "id": 2,
      "name": "Verify Invoice",
      "cta": "FORM_SUBMIT"
    }
  ],
  "employee/stats": {
    "tasks": {
      "allotted": 100,
      "completed": 200
    },
    "average_completion_time": "80 Sec"
  },
  "task": [
    {
      "id": 1,
      "task_config": {
        "name": "Verify RC"
      },
      "workflow": {
        "entity_type": "Order",
        "entity_id": 1
      },
      "tag": {
        "name": "Overdue",
        "type": "SLA_BREACH"
      }
    },
    {
      "id": 2,
      "task_config": {
        "name": "Verify Invoice"
      },
      "workflow": {
        "entity_type": "Order",
        "entity_id": 2
      }
    }
  ]
}
