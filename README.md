# h4nszizworks-dot.github.io

<form action="https://formspree.io/f/mjgdpddj"
      method="POST"
      enctype="multipart/form-data">

    <div class="form-group">
        <label>Nama Pengamat / Observer Name</label>
        <input type="text" name="observer_name" required>
    </div>

    <div class="form-group">
        <label>Departemen / Department</label>
        <input type="text" name="department">
    </div>

    <div class="form-group">
        <label>Lokasi / Location</label>
        <input type="text" name="location">
    </div>

    <div class="form-group">
        <label>Tanggal / Date</label>
        <input type="date" name="date">
    </div>

    <div class="checkbox-group">

        <label>
            <input type="checkbox"
                   name="observation_type[]"
                   value="Unsafe Action">
            Unsafe Action
        </label>

        <label>
            <input type="checkbox"
                   name="observation_type[]"
                   value="Unsafe Condition">
            Unsafe Condition
        </label>

        <label>
            <input type="checkbox"
                   name="observation_type[]"
                   value="Safe Action">
            Safe Action
        </label>

        <label>
            <input type="checkbox"
                   name="observation_type[]"
                   value="Safe Condition">
            Safe Condition
        </label>

    </div>

    <textarea name="observation"
              placeholder="Observation"></textarea>

    <textarea name="immediate_response"
              placeholder="Immediate Response"></textarea>

    <textarea name="recommendation"
              placeholder="Recommendation"></textarea>

    <input type="file" name="photo">

    <button type="submit">
        Submit SOCA Report
    </button>

</form>
