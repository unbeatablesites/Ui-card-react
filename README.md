# Ui-card-react
Clean card for react


import React from "react";

const service = "Service";
const alertId = "ID";
const serviceGroup = "Group";
const AssignedTo = "Assigned to";

const HelloBootstrap = () => (
  <div class="container card col-sm-3">
    <div class="row">
      <div class="mx-auto card-body ">
        <div class="d-inline p-2 bg-primary text-white">{service}</div>{" "}
        <div class="d-inline p-2 bg-dark text-white">{alertId}</div>{" "}
        <div class="d-inline p-2 bg-primary text-white">{serviceGroup}</div>{" "}
        <div class="d-inline p-2 bg-dark text-white">{AssignedTo}</div>
        <hr />
        <p class="overflow-auto card-text">
          This is a longer card with supporting text below as a natural lead-in
          to additional content. This content is a little bit longer. This is a
          longer card with supporting text below as a natural lead-in to
          additional content. This content is a little bit longer.
        </p>
      </div>
    </div>
  </div>
);

export default HelloBootstrap;
