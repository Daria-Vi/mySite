<h1>Домовой, 2024</h1>
<script>
    import img from '$lib/images/logo2.jpg';
</script>
<img src={img} alt="logo" width="40%" height="65%"/>
<br>
<p>Осиротев, Варя и Арсений перебираются из родной деревни в дом к приемным родителям. Но надежда на счастливую жизнь угасает, когда им бросает вызов древняя потусторонняя сила.</p>
<br>
<p>Продолжительность:    1 час 35 минут<br>
    Год выпуска:     2024<br>
    Премьера в России:     4 апреля 2024<br>
    Премьера в мире:     4 апреля 2024<br>
    Возраст:     16+</p>
<!--
<form on:submit|preventDefault={addExpense}>
 <label for="name">Название:</label>
 <input type="text" id="name" bind:value={newName} />
 <label for="amount">Сумма:</label>
 <input type="text" id="amount" bind:value={newAmount} />
 <button type="submit">Добавить</button>
</form>

<table>
 <thead>
  <tr>
   <th>Название</th>
   <th>Сумма</th>
   <th>Действия</th>
  </tr>
 </thead>
 <tbody>
  {#each expenses as expense, i}
   <tr>
    <td><div>{expense.name}</div> </td>
    <td><div>{expense.amount}</div> </td>
    <td><button on:click={() => deleteExpense(i)}>Удалить</button></td>
   </tr>
  {/each}
 </tbody>
</table>

<script>
 let expenses = [];

 let newName = '';
 let newAmount = '';

 function addExpense() {
  const obj = {
   name: newName,
   amount: parseInt(newAmount),
  };
  expenses.push(obj);
  expenses = expenses;
  newName = '';
  newAmount = '';
 }

 function deleteExpense(index) {
  expenses.splice(index, 1);
  expenses = expenses;
 }
</script>-->

<style>
 label {
  display: block;
  margin-bottom: 10px;
 }
 input[type='text'] {
  padding: 5px;
  border: 1px solid #ccc;
  margin-right: 10px;
  width: 150px;
 }
 table {
  margin-top: 20px;
  border-collapse: collapse;
  width: 100%;
 }
 thead {
    color: #4a0e72;
;
 }
 th, td {
  border: 1px solid #4a0e72;
  padding: 8px;
  text-align: center;
 }
 th {
  background-color: #eee;
 }
 button {
  padding: 5px 10px;
  background-color: #5744c5;
  color: white;
  border: none;
  cursor: pointer;
 }
 h1 {
  font-size: 24px;
  margin-bottom: 20px;
 }
</style>