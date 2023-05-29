GetEvaluationById
GET /evaluations/id/{id}

GetEvaluationsByType
GET /evaluations/type/{type}

CreateOrUpdateEvaluationVote (INSERT / UPDATE)
POST /users/{id}/evaluation-vote

GetEvaluationVotesByUserId
GET /users/{id}/evaluation-vote

GetEvaluationVotesByUserIdAndVoter
GET /users/{id}/evaluation-vote/voter/{voterId}

DeleteEvaluationVote (DELETE)
DELETE /users/{id}/evaluation-vote/{evaluationId}/voter/{voterId}/

GetAverageUserEvaluationsByType
GET /users/{id}/evaluation-vote/type/{type}/average