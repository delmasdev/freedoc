<!DOCTYPE html>
<html>
<body>
  <div>
  <h1>App ruby FreeDoc - THP</h1>
    <h2>Delmas</h2>
      <h3>Ruby version: 2.5.1</h3>
   <h2>How to install and test?</h2>
      <h4>Download or clone the repository</h4>
        <code>$ git clone https://github.com/delmasdev/freedoc.git</code>
      <h4>Run the command bundle install to install the necessary gems</h4>
        <code>$ bundle install</code>
      <h4>Update your database structure with the migration command.The database in not uploaded to github, so it is necessary tu run the differents migrations:</h4>
        <code>$ rails db:migrate</code>
      <h4>Add data into your database with the seed file:</h4>
        <code>$ rails db:seed</code>
      <h4>Open the rails consol with rails consol command and check if datas have been created by using the following command:</h4>
        <code>$ rails c</code>
      <h4>Use Table Print Gem with "tp"<h4>
        <code>tp Doctor.all</code>
        <code>tp Patient.all</code>
        <code>tp Appointment.all</code>
        <code>tp City.all</code>
        <code>tp Specialty.all</code>
        <code>tp DealWithIt.all</code>
      </div>
      <div>
        <h2>Database structure: has_many_through</h3>
        <p>6 tables:</p>
        <ul>
          <li>doctor</li>
          <li>patients</li>
          <li>appointments</li>
          <li>cities</li>
          <li>specialties</li>
          <li>deal_with_its</li>
        </ul>
     </div>
</body>
</html>